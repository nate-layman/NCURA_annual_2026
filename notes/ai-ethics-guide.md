# An Introductory Guide to AI Ethics: Questions, Concepts, and Methodologies

Figuring out how to use AI tools ethically requires two complementary skills: knowing which questions to ask and knowing how to look for answers. This guide draws on philosophical approaches to critical thinking and ethics to introduce both.

## Helpful Concepts and Distinctions

### Individual and collective action

Ethical questions about AI arise at both levels. What is ethical for an individual to do may differ from what produces the best collective outcome, and vice versa.

### Tragedy of the commons, prisoner's dilemmas, and the stag hunt

These are well-known models of situations where individual incentives can conflict with collective well-being. They help us think about why ethical AI adoption can be hard even when everyone agrees on the goal — the structure of the situation itself can push people toward worse outcomes. If you are not familiar with these, see the Appendix below.

### Descriptive ("is") vs. normative ("ought")

- **Descriptive claims** are about what is the case or what is possible.
- **Normative claims** are about what ought to be the case or what is permissible.

### The Naturalistic Fallacy

You cannot derive an "ought" from a mere "is." The description "Someone is texting and driving" does not justify the claim "It is permissible to text and drive."

That said, there is a connection: the principle **"ought implies can"** holds that if something ought to be the case, it must be possible. When we hold someone morally responsible, we expect it was possible for them to have acted otherwise.

### Normative inquiry requires normative starting points

Unlike empirical sciences, normative domains like law and ethics cannot rely solely on observation. We always begin with some normative assumptions, then expand and refine them into principles and generalizations. The question is: How? The next section provides a brief introduction to some methodologies.

---

## Methodologies for Normative Inquiry

### Argument by Analogy

Arguments by analogy are one of the most common tools in ethical reasoning. They have the following form:

> In situation X, there is a moral obligation to (or it is not permissible to) do A. Situation Y has the same relevant features as situation X. Therefore, in situation Y there is also a moral obligation to (or it is not permissible to) do A.

**Example:** "Introducing a new AI tool is like a new prospective medication. Clinical medicine prioritizes safety, has strong regulatory oversight, and criteria for what is permissible. Therefore, AI technologies should also prioritize safety and have regulatory oversight for what is permissible."

**To criticize an argument by analogy:** Identify relevant dissimilarities between X and Y. What counts as relevant is itself discovered and assessed through dialogue.

### Reflective Equilibrium

Reflective equilibrium is a way of working toward a consistent ethical position by going back and forth between your gut reactions to specific cases and the broader principles you hold. The idea is that neither your instincts nor your principles are automatically right — instead, you adjust both until they fit together.

Here's how it works in practice:

1. **Start with a gut reaction.** You encounter a case and have a strong sense of what's right or wrong. For example: "It feels wrong to let an AI system make hiring decisions without any human review."
2. **Try to articulate why.** What principle is behind that reaction? Maybe: "Decisions that significantly affect people's lives should involve human judgment."
3. **Test it against other cases.** Does that principle hold up? What about a doctor using an AI diagnostic tool — should a human always override it, even when the AI is more accurate? You might feel less sure here.
4. **Adjust.** Maybe the principle needs refining: "Decisions that significantly affect people's lives should involve human judgment, but the role of human judgment may vary depending on the stakes and the reliability of the tool."
5. **Bring in broader ethical considerations.** Does a utilitarian perspective (maximizing overall well-being) push you in a different direction than a rights-based perspective (protecting individual autonomy)? Weigh these against each other.
6. **Repeat.** Keep testing your refined principles against new cases and adjusting until your positions feel coherent — not perfect, but consistent and defensible.

The goal isn't to arrive at a final answer. It's to develop a position you can articulate and defend, while remaining open to revising it when you encounter new cases or arguments.

Both argument by analogy and reflective equilibrium are iterative and work best through dialogue — whether informal conversation or formal publication.

---

## Guiding Questions

The following questions are starting points. As you work through them, more questions will emerge — that's a feature, not a bug. The follow-up questions will be more specific to your context, and the process of working through them reveals important assumptions and differences that inform decision-making.

### 1. Who is made vulnerable by the AI tool?

- Who is "downstream" from you — who depends on the work you do?
- Who is "upstream" from you — who do you depend on?

### 2. How can potential harm be minimized?

This question reflects individual-centric ethical frameworks that prioritize respecting agency. Any benefits to the many are largely discounted against the potential harms of a few.

- **Example:** In clinical medicine, trials are first done to ensure a prospective treatment is safe.
- **Example:** The EPA's default model presumes that each increase in exposure to a substance like a carcinogen yields increased risk of harm.
- **Related concepts:** Justice, fairness, equity, rights, Deontology, Care Ethics.

### 3. Who stands to benefit from the AI tool? How can benefits be maximized and distributed?

- How do you go about finding that out?
- The question about maximizing benefits reflects utilitarianism, which tends to emphasize collectives. Harms and benefits are balanced against each other; the harms to a few can be counterbalanced by benefits to the many.
- **Examples:** Cost-benefit analysis in risk management, finance, military operations.

### 4. Can the adoption be reversed?

We face moral uncertainty when we are unsure which ethical framework to adopt or how to balance competing considerations. A useful strategy: favor reversibility — keep as many options open as possible so we can change course later.

- **Reversible actions:** Writing with a pencil, scheduling meetings, archiving emails.
- **Irreversible actions:** Spilling ink on paper, permanent deletion of files, publishing sensitive information.

**Key follow-ups:**

- What plans are in place to detect issues that signal it's time to change course?
- What procedures allow for intervention if needed?
- Do the AI tools we adopt allow interventions to be possible? (A key question in AI Safety.)

---

## Resources for Exploring AI's Environmental Footprint

**what-uses-more.com** Compares energy and water costs of everyday digital activities using consistent units (Wh/hr, mL/query). Created by Jon Ippolito, Professor of New Media, University of Maine. Also available as a custom ChatGPT GPT.

**your-digital-life.org** Helps students explore the environmental footprint of their own digital habits and see how AI fits into their broader digital life. Created by Joel Gladd.

**ai.uidaho.edu/gpu_telemetry_analysis.html** Analyzes the environmental footprint of the University of Idaho's GPU cluster using real telemetry data — annual emissions are equivalent to about 9 US households, with location on Idaho's hydroelectric grid cutting carbon intensity to roughly a third of the national average.

All three resources ground the environmental conversation in real data, but from different angles — comparative energy costs, personal digital habits, and institutional infrastructure — making them worth examining together.

---

## Appendix: Collective Action Problems Illustrated

The scenarios below show how the structure of a situation — not the intentions of the people in it — can lead to bad outcomes. Recognizing which structure you're in helps you think about what kind of coordination, regulation, or trust-building might be needed.

### Tragedy of the Commons

A shared resource is open to everyone. Each person benefits by using more of it, but if everyone does, the resource is depleted and everyone loses.

**Classic example:** A group of herders shares a common pasture. Each herder benefits from adding one more animal. But if every herder does this, the pasture is overgrazed and collapses — leaving everyone worse off.

**AI connection:** Compute-intensive AI models consume shared resources like energy and water. Any one organization benefits from training larger models, but if everyone races to scale without constraint, the cumulative environmental cost is borne by all. The same logic applies to data — scraping freely available content benefits individual model-builders, but unchecked extraction can degrade the commons of publicly shared knowledge.

### The Prisoner's Dilemma

Two parties would both be better off cooperating, but each has an individual incentive to defect — and if both defect, both end up worse off than if they had cooperated.

**Classic example:** Two suspects are interrogated separately. If both stay silent (cooperate), they each get a light sentence. If one betrays the other (defects) while the other stays silent, the betrayer goes free and the silent one gets a harsh sentence. If both betray each other, both get moderate sentences. The rational move for each individual is to betray — but mutual betrayal is worse for both than mutual cooperation.

**AI connection:** Two universities might both benefit from adopting shared, transparent AI-use policies (cooperating). But each faces a temptation to quietly adopt AI tools with fewer guardrails to gain a competitive edge (defecting). If both defect, neither has meaningful standards, trust erodes, and everyone — students, faculty, the public — is worse off.

### The Stag Hunt

Cooperation produces the best outcome for everyone, but only if everyone commits. If you're not sure others will cooperate, the safer choice is to go it alone — even though that leads to a worse collective result.

**Classic example:** A group of hunters can work together to catch a stag (big payoff for all), but only if everyone participates. Any individual hunter can break off to catch a rabbit (small but guaranteed payoff). If even one person goes for the rabbit, the stag hunt fails. The dilemma isn't about temptation to cheat — it's about trust. You'd prefer to cooperate, but only if you're confident others will too.

**AI connection:** A department might agree that everyone will use AI tools transparently and develop shared norms around attribution and quality. This works well if everyone commits. But if you suspect your colleagues won't follow through, the safer move is to just do your own thing — which means the shared norms never take hold. The stag hunt highlights why building trust and visible commitment matters for collective AI governance.
