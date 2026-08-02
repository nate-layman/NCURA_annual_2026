# AI Literacy Course: Gaps and Open Questions

A working punch list of what is missing, unresolved, or promised-but-not-yet-built across the course. Based on Modules 1-4 drafts, the course overview, and the NCURA session abstract as of 2026-08-02.

Priority tags: **[Blocker]** = ship-blocking. **[Fix]** = ship with it, but flag. **[Nice]** = future improvement.

---

## Cross-cutting

- **[Blocker] Module 5 (AI Use Cases) is not drafted.** Only a topic list exists in the course overview. Financial, Cost Accounting, and Contract Review subcategories have suggested fill-ins from Nathan pending Dashiell / SUU review. No worked examples, no activity, no assessment.
- **[Blocker] Module 5 purpose statement is mis-slotted.** The stated purpose ("strategies for ongoing learning and adaptation in an AI-driven environment") reads like Module 6's purpose. Fix in course-overview.md.
- **[Blocker] Assessment infrastructure not built.** Course overview promises mini quizzes per module plus a final comprehensive assessment. No quiz items authored, no LMS integration decided, no scoring rubric.
- **[Blocker] Pre/Post surveys not built.** Required for NSF external evaluation plan. Instruments not documented, delivery mechanism not decided.
- **[Blocker] Certificate mechanism undefined.** Completion certificate promised. Generation, delivery, and tracking pathway not specified.
- **[Fix] Hosting and technical infrastructure unclear.** NCURA to host free content per the partnership answer, but the platform, LMS choice, and NSF open-source packaging (Creative Commons? GitHub? LMS-agnostic export?) are not documented.
- **[Fix] Interactive components sparse.** Course structure promises "interactive games." Only Promptulus (Module 3) and the Workshop Instrument (Module 2) are named. Module 1 references an "AI Myths vs. Facts" quiz that is not built. No games in Modules 4 or 5.
- **[Fix] Videos.** Course structure references "short videos." Only external videos linked so far (NCURA YouTube via Module 1). Original video content plan not documented.
- **[Fix] Cross-module consistency check needed.**
  - Data-privacy definitions overlap Modules 2 and 4 (KG2, KG3 flagged this). Agree on shared definitions.
  - Section numbering conventions differ (Module 1 has 1.1, 1.2 style; Module 2 restarts at "1.1" inside Section 2; CJ1 in Module 2 flagged this).
  - Module 2 references "TaMPER" and Module 3 references "TaMPER Framework" (via course overview); Module 1's TaMPER treatment is undefined. KG7 flagged this.
  - Header discrepancies: Module 1 says "1 of 5" but a reviewer asked "1 of 4?" Course overview confirms 5 modules.
- **[Fix] Reviewer comments unresolved.** Roughly 50+ across the four drafts. Comment counts: Module 1 ~17 (CJ1-22 + NL/TD), Module 2 ~40+ (partially captured, source was truncated), Module 3 26, Module 4 8.
- **[Nice] Whole-course vocabulary/glossary not built.** TD34/TD35 in Module 3 suggested this. Would tie modules together and support the "define foundational AI concepts" LO.
- **[Nice] Contributor/author attribution list.** Reviewer initials (CJ, KG, MM, TD, NL, BB) not documented anywhere central. New collaborators will not know who is who.
- **[Nice] Bibliography deduplication and completeness.** Each module has its own references; overlap not managed. MM36 in Module 3 asked for verification and noted missing citations (e.g., OIT AI Literacy course).

---

## Module 1: Introduction to AI in Research Administration

- **[Fix] Structural / numbering errors.** Section 2 restarts at "1.1" instead of 2.1. "1.4" appears twice (Human-Centric View and Crowd of Amateurs). Knowledge Check Q1 references "Section 7" and "Section 5" that do not exist in this module.
- **[Fix] Duplicated paragraphs.** Section 1.4 states the three-legs-of-assurance point twice. Crowd of Amateurs states the "polling twice / good at consensus" idea twice.
- **[Fix] Typos and grammar.** "GTP-4" (twice), "AI remains perfect" (should be "isn't"), "AI use in RA can recognized" (missing "be"), "basic pattern remains largely has been stable", "requrie" (Tier 1).
- **[Fix] Summary/body mismatch.** Summary table lists "document assistant" as a mental model; Section 4.2 has "Research Assistant."
- **[Fix] Placeholder figure (NL12).** Agentic loop figure noted as "not 100% yet."
- **[Fix] Harmon video citation format.** CJ4 flagged that we need to decide how to cite the NCURA-supported video once the mode of communication is settled.
- **[Fix] AI Myths vs. Facts quiz.** Course overview promises this as the Module 1 activity. Not built.
- **[Open] Environmental cost bullet placement.** NL8 and CJ9 debated whether the compute/environmental line belongs under "AI is not magic" or elsewhere.
- **[Open] Multiple review requests to Nathan or Dashiell.** CJ5, CJ10, CJ11, CJ16, CJ17 flagged for input.

---

## Module 2: Ethical and Responsible AI Use

- **[Blocker] Workshop Instrument web app.** Section 3 of the module is built around this activity and returns to it in Sections 10.1 and 11.1. BB2 asks whether the plan is still to build it; BB3 notes the module was mistakenly assumed to sit after Prompt Engineering. If the instrument is not built, Sections 3, 10.1, and 11.1 collapse.
- **[Blocker] Live-demo scenarios.** Section 1.2 and Section 4.1 both open with a "live demo placeholder." TD4 asks whether these exist or need creating; BB5 confirms they need to be created.
- **[Fix] Audience unclear.** CJ6 asks whether the document is for RAs (the learners) or for trainers guiding RAs. Framing decisions in Section 3 depend on this answer.
- **[Fix] Sectioning inconsistent with Module 1.** CJ1 flagged that Module 2 lacks a module-overview + learning-objectives header pattern that Module 1 uses.
- **[Fix] Reflective Equilibrium Cycle infographic (Section 9).** Placeholder; same status as Module 3's Prompt Engineering Cycle infographic.
- **[Fix] Structural typos and duplicated text.** Multiple sentences read as if a track-changes merge went wrong ("this basic pattern remains largely has been stable", "one is described as a workhorse [...] The idea is that:"). Full copy-edit pass needed.
- **[Fix] Reviewer comments partially lost.** The source text pasted for conversion was truncated at TD15; CJ16-36, TD26-28, TD33, TD37-41, and BB39 have placeholder text in the markdown. Retrieve full comments from original source.
- **[Open] "Cost of skipping ethical reasoning" section (Section 5).** Original AI Ethics Guide did not include this; the draft author added it as a parallel to Module 3's cost-of-poor-prompting section. Bert should confirm the failure-mode list matches what he wants to flag.
- **[Open] "Find the Dissimilarity" exercise (Section 11.2).** Original to this draft; Bert may want to substitute an analogy more specific to UAI's context.
- **[Nice] Additional references.** Rawls (1971) and Daniels' SEP entry on reflective equilibrium are candidates if more grounding is wanted.

---

## Module 3: Prompt Engineering for Research Administration

- **[Blocker] Bert's puzzles (Exercise 2, Section 9.2).** MM31 says Bert will need to provide these. BB32 confirms it depends on Promptulus-adjacent capability. Not built.
- **[Blocker] Promptulus hosting decision (Section 8.2).** Where Promptulus will live for the course and what URL learners should be sent to is unresolved. Determines whether Section 9.1 exercise is executable.
- **[Blocker] Prompt Engineering Cycle infographic (Section 7).** MM26 flagged; placeholder only.
- **[Fix] Six supporting example documents referenced but existence uncertain.**
  - Examples of Poor RA Prompts
  - Examples of Typical RA Prompts
  - FOA Example of Poor vs Well-Engineered Prompt
  - Personnel Costs Justification Example
  - Unallowable Costs Example
  - Your AI Has a Page Limit blog post
  - MM18/BB19 flagged this specifically for the FOA example.
- **[Fix] Vandalizer/Promptulus mention feels promotional.** MM23, BB24, TD25 discussed at length. Decide framing and whether to add a workflow graphic.
- **[Fix] Definitional tension.** CJ21/CJ22 flagged that "prompt engineering" is used one way in Sections 2-5 and re-scoped in Section 6 (to distinguish it from context engineering). Rewrite for consistency or rename to "prompt craft."
- **[Fix] Template library reference.** TD29 suggested a "How to create your own library" section with a bracketed template example. TD30 noted the AI4RA GitHub prompt library could be linked. Not integrated.
- **[Fix] References incomplete.** MM36 asked to verify citations. OIT AI Literacy course citation missing (Michele to add). "Your AI Has a Page Limit" link marked TO DO.
- **[Nice] Poor Prompt Test framing.** TD11 suggested reframing from "your prompt is probably too poor if" to more diagnostic "look for these kinds of things." CJ13 suggested renaming to something like "pitfalls in prompt engineering."

---

## Module 4: Compliance, Risk, and Institutional Governance

- **[Fix] Compliance Pyramid figure is a placeholder.**
- **[Fix] Approved AI Services table/figure is a placeholder.** Screenshot from UI OIT KB referenced.
- **[Fix] Data classification / privacy definitions duplicate Module 2.** KG2, KG3 flagged. Coordinate with Module 2 on shared definitions.
- **[Fix] Data classification questions list needs prioritization.** KG4 asks for top 3-5 to avoid overwhelming readers. KG5 suggested a specific top-3. Not yet applied.
- **[Fix] Export controls section needs subject-matter fact-check.** KG6 flagged.
- **[Fix] Ethical AI section (Section 4.4).** KG8 asks for a brief mention that references Module 2's language for consistency.
- **[Open] Dropped Section 4.5.** KG1 outlined "Coordinating with Campus Services for Responsible AI Adoption" (IT, Legal, IRB, OSP collaboration) as a possible section. Decision to fold-in or restore.
- **[Open] Case example placeholder.** From KG1's dropped Section 4.5: "How cross-campus coordination prevented an AI data leak or compliance breach." No case yet identified.
- **[Nice] Multiple sponsor and state URLs need verification.** Long-lived UTM parameters and section anchors may rot.

---

## Module 5: AI Use Cases

- **[Blocker] Module not drafted.** Only a topic list exists in course overview.
- **[Blocker] Financial / Cost Accounting / Contract Review sub-bullets.** Nathan's suggested fill-ins are in place but marked "pending team review." Need confirmation from Dashiell and SUU.
- **[Blocker] Activity not defined.** Every other module has an activity; Module 5 does not.
- **[Blocker] Purpose statement misassigned.** Currently reads as Module 6's purpose.
- **[Blocker] Depends on UI + SUU tool development.** Course overview notes: "additional use cases as our team works with the University of Idaho and Southern Utah University on the development of specific AI tools."
- **[Fix] Poisoned-PDF example under Post-Award.** Concept mentioned but no worked example.
- **[Fix] Vandalizer integration.** Given Module 3's Vandalizer discussion, Module 5 use cases likely map to Vandalizer workflows. Not yet linked.

---

## Module 6: Current Events and Updates in AI

- **[Fix] Website page not built.** Living updates page infrastructure not decided.
- **[Fix] Quarterly live presentation plan.** Cadence, host, format, promotion not documented.
- **[Fix] Curation policy.** Who chooses what appears? Editorial standard? Frequency?
- **[Fix] Overlap with Module 5 purpose statement.** See cross-cutting note.

---

## NCURA Session (August 2026)

Relevant to the concurrent-session deck at [docs/ai-literacy.html](../docs/ai-literacy.html), previewing gaps between the session abstract and the deck as delivered.

- **[Fix] "Interactive exercises and discussions"** (from abstract) not represented on the deck. Live Promptulus moment or a "your turn" prompt during four-reasons could close this.
- **[Fix] "Break complex tasks into manageable components"** (LO 3) is thinly represented. Module 3 seven-components covers piece of it; the "break down complex tasks" framing is missing.
- **[Fix] "Iterative refinement strategies"** (LO 5) is one Promptulus bullet on Module 3 slide. Would benefit from a dedicated moment or slide.
- **[Nice] Bridge slide between Part 3 (AI literacy definitions) and Part 4 (four reasons).** Transition currently jumps from theory to practical implications with no connective slide.
- **[Nice] Course enrollment / CTA slide (Slide 22) needs real URL.** Currently ai4ra.uidaho.edu is listed; confirm this is the correct enrollment landing page or replace.

---

## Immediate next steps

If we are ranking by what would most reduce risk of the course not shipping:

1. Draft Module 5 (Blocker on shipping the course).
2. Decide Workshop Instrument fate (Blocker on Module 2 shipping).
3. Decide Promptulus hosting (Blocker on Module 3 exercises).
4. Build assessment infrastructure (Blocker on completion certification).
5. Build pre/post surveys (Blocker on NSF evaluation compliance).
6. Copy-edit pass on Modules 1 and 2 (many small errors will accumulate reader friction).
7. Resolve the 50+ reviewer comments.
