# AI Literacy Deck Style Guide

For the NCURA Annual 2026 concurrent-session deck at [docs/ai-literacy.html](../docs/ai-literacy.html) and future decks that share the AI4RA visual system.

Synthesized from Alley (Assertion-Evidence), Duarte (Glance Test, slide:ology), Reynolds (Presentation Zen), Beautiful.ai, HubSpot, and the SketchBubble ruleset. Full source list at the bottom.

---

## Philosophy

Four principles, in priority order:

1. **One idea per slide.** If a slide covers two ideas, split it.
2. **Assertion headline.** The headline is a full declarative sentence stating the takeaway, not a topic label. Two lines max.
3. **Passes the 3-second glance test.** If a reader can't parse the slide in three seconds, redesign it.
4. **Deck-wide consistency.** Apply the ruleset without exception. Breaking your own rules feels amateur.

Everything below serves those four.

---

## Type hierarchy

| Element | Size | Weight | Class | Notes |
|---|---|---|---|---|
| Slide headline (assertion) | 2.2rem | 800 | `h2` | One idea, one sentence, two lines max |
| Hero title (title / close) | 2.8rem | 800 | `h1` | Reserved for title and close slides only |
| Card / subhead | 1.15rem | 800 | `h3` | Inside cards and sub-sections |
| Body | 1.18rem | 400 | `p`, `li` | Muted color (`--muted`) |
| Kicker | 0.8rem | 800 | `.slide-kicker` | Uppercase, gold, letter-spacing 0.16em. Use sparingly. |
| Lede | 1.18rem | 400 | `.slide-lede` | Short paragraph under the headline. Max 36rem. |
| Callout | 0.95rem | 700 | `.slide-callout` | Highlighted takeaway box, gold left border |
| Quote | (inherit) | 400 | `.slide-quote` | Blockquote-style |
| Source note | (inherit) | 400 | `.slide-note` | Attribution, small |

**Word budget per slide:** aim for under 50. Above 75 = document, not a slide.

**Fonts:** system sans stack only. No custom webfonts unless we own the license.

---

## Color palette

Confined, deliberate. Use only these:

| Role | Value | Use |
|---|---|---|
| Ink (primary text) | `#191919` (`--ink`) | Headlines and body |
| Muted (secondary text) | `#555` (`--muted`) | Body paragraphs, notes |
| Background | `#fafaf7` (`--bg`) or white | Every slide |
| Accent | `#f1b300` (`--gold`) | Kickers, callout borders, card accent background |
| Card fill | `rgba(25,25,25,0.04)` | `.slide-card` default |
| Card accent fill | `rgba(241,179,0,0.14)` | `.slide-card.accent` |

**No dark slides.** No `data-background-color="#191919"`. No yellow-background slides either (title and close use white).

**Emphasis:** color or weight only. No underlines, no ALL CAPS in body (kickers are the one exception), no italics-for-emphasis.

---

## Layout patterns

Pick the pattern that fits the content, then apply it verbatim. Consistency across slides matters more than local optimization.

### 1. Assertion + evidence (default for text-forward slides)

Full-sentence H2 headline at the top. Below: one visual (image, chart, diagram, quote) or a short body paragraph. No bullets unless there is a genuine list.

Structure:
```html
<section>
  <h2>Declarative assertion. Two lines max.</h2>
  <p class="slide-lede">Optional one-line elaboration.</p>
  <div class="slide-callout">Optional highlighted takeaway.</div>
</section>
```

### 2. Split (image accent)

Text-forward slides that would benefit from a visual anchor. Image occupies the left ~45%, text the right ~55%, both vertically centered.

Uses `.slide-split` with `.split-img` and `.split-text` children. Image max height 12em. Use `.slide-split.img-wide` if the image needs 65% (rare).

```html
<section>
  <div class="slide-split">
    <div class="split-img">
      <img src="img/slides/xxx.jpg" alt="Descriptive alt text" />
    </div>
    <div class="split-text">
      <p class="slide-kicker">Optional kicker</p>
      <h2>Assertion.</h2>
      <p class="slide-quote">Content.</p>
    </div>
  </div>
</section>
```

### 3. Card grid

Comparison slides, "three tiers" style slides, side-by-side concept slides. Cards are the visual — no image needed.

- 2 concepts: default `.slide-grid tight` (2-col)
- 3 concepts: override to `grid-template-columns: repeat(3, ...)`
- 4 concepts: default `.slide-grid tight` (2×2)

Always add `style="align-items: stretch;"` on the grid so cards match height. Never put `height: 100%` on the cards themselves (causes reveal.js layout overlap).

```html
<div class="slide-grid tight" style="align-items: stretch;">
  <div class="slide-card accent"><h3>Label</h3><p>Body.</p></div>
  <div class="slide-card accent"><h3>Label</h3><p>Body.</p></div>
</div>
```

### 4. Quote slide

For canonical quotes (definitions, authoritative citations). One quote per slide when possible. Use `.slide-quote` for the quote text, `.slide-note` for attribution.

If it needs an image accent (e.g., a portrait or a related photo), wrap in `.slide-split`.

### 5. Hero (title and close only)

Two slides in the deck: the title and the "Questions?" close. Uses the `.title-slide` class. Center-aligned. No image background. Author line at the bottom with `font-weight:700`.

### 6. Interactive widget

Slido poll, Task Sorter, Trust Rater, Character Grid, Context Slider, Token Builder, Toggle Compare, Challenge Checklist, Flip Cards.

- Never add background images to interactive slides — they compete with the widget.
- Kicker OK. Headline OK, kept short.
- The widget is the visual load.

### 7. List (numbered / bulleted)

Ranked lists or step-by-step items. Left-aligned, constrained to `max-width: 38rem`, centered on slide.

```html
<ol style="text-align:left; max-width:38rem; margin-left:auto; margin-right:auto;">
  <li><strong>Item</strong> &middot; brief description.</li>
</ol>
```

---

## Image use

**Images are accents, never backgrounds.** No `data-background-image`.

Placement patterns:
- **Split accent:** image at 45% of slide width (see Layout 2)
- **Hero centered:** image above headline, centered, max 300px wide (for title-style slides if needed)
- **Icon accent:** small icon inline with a heading (~40-60px)

Every image must:
- Be sharp at its rendered size (2x for retina)
- Directly support the slide's assertion
- Come from a free-use source (Unsplash, Pexels, Pixabay, Wikimedia Commons) or be original

No: watermarked stock, glowing brains, faceless robots, blue-matrix code, generic handshakes, template clip-art.

Live images (people, hands, natural objects) beat abstract stock. Illustration (like the Promptulus companions) beats generic photography when a repeatable visual system already exists.

---

## Spacing and grid

Every element should feel like it snaps to an invisible grid. Consistency > cleverness.

- Slide default padding: as set by reveal + `.reveal .slides section` (0.4rem top)
- Callouts: `margin-top: 0.8rem` (from CSS)
- Grid gap: `1rem` (or `0.8rem` with `.tight`)
- List max width: `36rem` for prose, `38rem` for lists, `44rem` for wider content
- Interactive components: `max-width: 44rem` for widgets like task-sorter, toggle-compare

**Whitespace is a design element.** Cut copy before shrinking margins.

---

## Assertion-Evidence template

Michael Alley's canonical structure (research shows measurably better retention):

```
[Full-sentence assertion at the top, 2 lines max]

[Single supporting visual: chart, diagram, photo — or short callout]

[Optional: source note]
```

Bad: `<h2>Prompt Engineering</h2>` + bullets
Good: `<h2>Prompt quality determines output quality.</h2>` + a diagram or callout

---

## Anti-patterns

Never do these:

- **Kicker + short title + short subtitle only.** Pure label slide. Fold into the content slide that follows.
- **Dark backgrounds.** Any `data-background-color` other than white or the yellow accent on non-title slides.
- **Yellow-background title/close slides.** White only.
- **Em dashes** (`—`, `&mdash;`, `--`). Use periods, commas, colons, or restructure the clause.
- **Background images.** Use split-layout accent instead.
- **Cards with `height: 100%` inline.** Causes reveal.js overlap. Use `align-items: stretch` on the grid instead.
- **Bullets on a slide that could be one sentence.** Convert to a callout.
- **More than one idea per slide.** Split into two.
- **Section-header slides that only carry a label.** Fold into content.
- **Template chrome, 3D chart effects, clip-art, watermarked stock.** Amateur signals.

---

## Deck-level defaults

- Reveal.js config: `hash: true, controls: true, progress: true, center: true, slideNumber: true, transition: "slide"`
- Slide dimensions: reveal defaults (960 × 700)
- Interactive JS: `docs/slides-interactive.js` (task sorter, spectrum, token builder, toggle, medallion, traffic-btn, flip-card)

---

## Sources

- Alley, M. *The Craft of Scientific Presentations* (Springer, 2013). [Assertion-Evidence](https://www.assertion-evidence.com/)
- Duarte, N. *slide:ology* (O'Reilly, 2008); *Resonate* (Wiley, 2010); [The 3-Second Test](https://www.duarte.com/blog/the-three-second-test/); [HBR Glance Test](https://hbr.org/2012/10/do-your-slides-pass-the-glance-test)
- Reynolds, G. *Presentation Zen* (3rd ed., New Riders, 2019); [presentationzen.com](http://presentationzen.com/blog/what-is-good-presentation-design)
- Tufte, E. *The Cognitive Style of PowerPoint* (Graphics Press, 2003)
- Mayer, R.E. *Multimedia Learning* (3rd ed., Cambridge, 2020) — coherence, redundancy, signaling principles
- Beautiful.ai — [Great presentations still need design rules](https://www.beautiful.ai/blog/ai-can-build-slides-fast--but-great-presentations-still-need-design-rules)
- SketchBubble — [7 Rules for Beautiful PowerPoint](https://www.sketchbubble.com/blog/want-beautiful-powerpoint-presentations/)
- HubSpot — [PowerPoint Tips to Present Like a Pro](https://blog.hubspot.com/marketing/easy-powerpoint-design-tricks-ht)
