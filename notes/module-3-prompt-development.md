# Module 3: Prompt Development for Research Administration

**Date:** April 27, 2026

## Table of Contents

- Module 3: Prompt Development for Research Administration
- 1. What is Prompt Engineering and Why It Matters
- 2. Defining Prompt Engineering
- 3. Why Prompt Engineering Matters in Research Administration
- 4. The Cost of Poor Prompting
- 5. The Components of an Effective Prompt
- 6. From Prompt Engineering to Context Engineering
- 7. The Prompt Engineering Cycle
- 8. Strategies for Refining Outputs
- 9. Quick Check for Understanding
- 10. Where to Go from Here
- Appendix A: Source Materials and Supplements
- Appendix B: References
- Drafting Notes (to be removed before publication)

## Module 3: Prompt Development for Research Administration

**Date:** April 27, 2026 **Status:** Working draft

**Purpose.** Learn how to communicate effectively with AI tools to produce accurate, relevant, and compliant outputs. By the end of this module you should be able to: (1) recognize the difference between a poor prompt and a well-engineered one, (2) assemble the components of an effective prompt for a research administration task, (3) manage think about the broader information environment your AI is working in (context engineering), and (4) iterate on prompts until they earn their keep.

---

## 1. What is Prompt Engineering and Why It Matters

### 1.1 Introduction

A prompt is the set of instructions, questions, and context you provide an AI system to get the result you need. The quality of your prompt directly determines [^cj1] the quality of the result. This is not a slogan: it is the single most important [^cj2] thing to understand before you start using AI tools in your daily work.

Think of prompt engineering as the difference between two ways of asking a colleague for help. The first: "Can you help me?" The second: "Can you create a step-by-step guide for onboarding new research administrators at our institution, focused on pre-award workflows, that fits on a single page?" The first is too vague to act on. The second is clear, specific, and actionable. AI tools work the same way. They are powerful, but they are not mind readers, and the difference between a useful response and a useless, or even misleading one is often two or three sentences of additional framing in the prompt.

### 1.2 Demo: Poor vs. Well-Engineered Prompt

Demo placeholder. Choose one paired example from the supporting examples folder (FOA summary, personnel justification, or unallowable-costs review) and walk through both prompts side by side, projecting the AI's actual output for each.

### 1.3 The AI Communication Challenge

The fundamental problem is that AI tools are powerful but need clear instructions to be useful. The familiar phrase here is "garbage in, garbage out": the quality of the output depends on the quality of the input. For research administrators, this is not hypothetical. The difference between a good prompt and a bad one is the difference between a five-minute task and a two-hour cleanup, between a compliant budget justification and one that gets returned by the sponsor, between catching an unallowable cost before submission and discovering it during an audit.

In short, prompting is a professional skill, not a parlor trick. It is worth practicing. [^cj3]

---

## 2. Defining Prompt Engineering

### 2.1 Demo: Typical Research Administrator Prompt

Demo placeholder. Pull one well-engineered example from "Examples of Typical RA Prompts" (the email to the PI about missing budget information, the award terms summary, or the closeout email) and walk through it as an example of what a thoughtful, real-world RA prompt looks like in practice.

### 2.2 What is a Prompt?

A prompt is the interface between human intent and AI capability. It is the place where you tell the model what you need, who needs it, and how it should be delivered. In a chat tool, this is whatever you type into the message box. In a more structured tool, the prompt may be split into pieces: a system instruction set up once and reused, a user message you type each tim [^cj4] e, and one or more attached documents [^cj5].

Whatever the form, the prompt is the only thing the AI has to go on. If you do not supply something, In the absence of clear instruction, the model will guess. Sometimes it will guess well. Often it will not. The prompt is the lever you have for turning guessing into reliable performance.

### 2.3 What is Prompt Engineering?

Prompt engineering is the practice of crafting prompts that reliably get the outputs you want. It is both an art and a science: an art because there is real creativity in figuring out how to frame a task so the model can do it well, and a science because the practice rewards structure, iteration, and testing. Recent research bears this out empirically. Atreja and colleagues (2024) ran a large multi-prompt experiment across four annotation tasks and three differenta variety of Large Language Models (LLMs) such as ChatGPT, Claude, Gemini and many others, and found that compliance and accuracy varied dramatically with prompt design — by as much as 55% on a single task, on the same data, with the same model. The wording, structure, and content of the prompt are not cosmetic choices:. Tthey have the power to change the answer completely.

The good news is that prompt engineering is a learnable skill. It improves with practice, and most of what makes a prompt good is not magic. It is the same kind of careful, audience-aware specification you already do when you brief a new colleague, write a memo to a PI, or draft a guidance document.

---

## 3. Why Prompt Engineering Matters in Research Administration

### 3.1 Demo: Poor vs. Well-Engineered Prompt

Demo placeholder. Pull a different paired example here than the one used in Section 1 — ideally the FOA summary if Section 1 used the budget review, or vice versa.

Research administration is an unusually high-stakes setting for AI use. The work involves federal regulations, sponsor-specific rules, institutional policies, and tight deadlines, often all at once. A vague prompt does not just produce a mediocre answer. It can produce a confidently wrong answer that nobody catches until it shows up in an audit, so the case for taking prompt engineering seriously is not abstract.

### 3.2 Efficiency and Productivity

Well-crafted prompts save time by reducing revision cycles. A useful rule of thumb from real-world examples: a poor prompt takes a few seconds to write and produces output that requires several minutes of cleanup, or that is completely unusable. A well-engineered prompt may take several minutes to write but can often be saved as a template and reused and produce output that needs only minor edits. The results are unfavorable for the simplified approach, [^cj6] particularly when the prompt is reused across multiple PIs, multiple proposals, or multiple awards.

### 3.3 Accuracy and Compliance

Vague prompts produce generic, potentially inaccurate outputs. Specific prompts help ensure compliance with federal regulations and institutional policies. Consider a prompt that asks an AI to "check this budget for errors." The model has no way to know which sponsor's rules apply, which version of 2 CFR 200 is in scope, what your institution's F&A and fringe benefit rates are, or whether cost share is allowed, so it produces something defensible-sounding but useless: the calculations seem to add up; you may want to verify that all costs are necessary and reasonable [^cj7]. A well-engineered version of that same prompt, supplied with the relevant regulations, the sponsor's RFP, and your institution's rate structure, can flag actual unallowable costs with regulatory citations and quantify the budget impact of fixing them.

### 3.4 Professional Quality

Engineered Strong prompts produce outputs that fit the research administration context: appropriate tone for a PI versus a program officer, appropriate level of detail for a faculty audience versus a leadership briefing, appropriate format for an email versus a presentation. Generic prompts tend to produce outputs that are obviously machine-generated. Engineered prompts produce outputs that read like they came from an experienced administrator.

### 3.5 Control and Accountability

Better prompts produce more predictable, more verifiable outputs. This matters for responsible AI use. If your prompt specifies what the AI should check for, what the output should look like, and what citations or evidence should accompany each claim, you can verify the output against your specification. If your prompt is "is this proposal okay to submit?" you have nothing to verify against. Good prompting situates the AI asis an accountability tool, not just a productivity tool.

---

## 4. The Cost of Poor Prompting

### 4.1 Demo: Poor Research Administration Prompts

Demo placeholder. Pull two short examples from the "Examples of Poor RA Prompts" document — Review this budget and Can they buy this? are good ones — and show the actual generic outputs they produce.

### 4.2 Common Patterns in Poor Prompts

A small set of mistakes account for most poor prompts. They are worth naming.

- **Over-brevity.** [^cj8] Trying to save thirty seconds on the prompt costs thirty minutes to fix the output.
- **No context.** [^cj9] The AI cannot read your mind about institutional policies, your relationship with the PI, or 2 CFR 200 allowability.
- **Vague objectives.** Help me or review this without specifying what kind of help or review.
- **Missing constraints.** No guidance on length, format, tone, or what to leave out.
- **No audience definition.** [^cj10] Who receives this output? What do they need to know? At what level?
- **Assumed knowledge.** Expecting the AI to know your institution's specific policies or procedures without telling it.
- **No verification strategy.** Not thinking about how you will validate the AI's output before it goes anywhere.

### 4.3 The "Poor Prompt Test"

Your prompt is probably too poor if any of the following are true: [^td11] [^cj12]

- You could use the same prompt at any other organization and it would mean the same thing. [^cj13] [^cj14]
- Someone else reading the prompt could not identify specific goals for the output. would not know what you actually want.
- The prompt is shorter than one full sentence.
- It contains no proper nouns: no sponsor name, no PI name, no guidelines or policies.
- The output requires more editing than writing from scratch would have.
- You cannot tell from the output whether it is compliant or accurate. [^cj15]
- You are using AI out of desperation rather than making a deliberate choice.

### 4.4 Trust but Verify

A point worth dwelling on: in research administration, fast and wrong is more dangerous than slower and right. Poor prompts optimize speed at the expense of accuracy, compliance, and usefulness. A good prompt also makes verification easier, because you have specified what the output should contain. If you asked for regulatory citations and there are none, you know to push back. If you asked for a specific format and the format is off, you know to redo it. Verification is built into the prompt. With a vague prompt, verification is left entirely to you, after the fact, with nothing to compare against. [^cj16]

---

## 5. The Components of an Effective Prompt

This is the heart of the module. A well-engineered prompt is not a single clever sentence. It is a structured request, often with seven recognizable parts. You will not always need every part for every task, but knowing the components lets you make informed decisions about what information is or is not necessary. assemble what you need.

### 5.1 Role (or Persona)

Tell the AI who the task is for. "You are a pre-award research administrator at the University of AI" is more useful than no role at all, because it cues the model to the vocabulary, regulatory landscape, and stakeholder relationships of that role. Specifying the role also implicitly narrows what counts as a reasonable answer.

### 5.2 Context

This is the situational background the AI needs to do the job: the sponsor, the institution, the project, the PI's experience level, the relevant rate agreements, the relationship history, the deadline. Context is where most poor prompts fail. A good rule: if a new staff member needs to know it before doing the task, the AI needs to know it too.

### 5.3 Instruction (the Task)

State the task plainly and specifically. "Draft a budget justification for the personnel section" is better than "write a budget justification." "Identify potentially unallowable or problematic costs and flag each as RED, YELLOW, or GREEN with regulatory citations" is better than "check this for errors." The instructions should answer two questions: what should the AI do, and what does the result need to enable?

### 5.4 Input Data

Input Wwhatever specific material the AI needs to work with: the RFP, the budget spreadsheet, the sponsor's guidelines, the draft email. Be explicit about distinguishing instructions from data. what data is versus what instructions are. Many prompt failures come from the model treating instructions as data or vice versa.

### 5.5 Output Format

Specify the structure of the response: headers, bullet points, tables, length, and any required elements (a "Quick Summary" box at the top, a "Red Flags" section at the end, citations after each claim). Format requirements = change what the model produces, because they force it to organize information in a way that is reviewable and verifiable.

### 5.6 Constraints

Tell the AI what not to do. Example: do not include fringe benefit rates here, that is a separate section; do not include unnecessary background about NIH rules, reviewers knows them; do not exceed two pages. Negative constraints are surprisingly powerful. They eliminate large classes of unwanted output without requiring you to anticipate every possible failure.

### 5.7 Examples (when useful)

For specialized tasks — particularly format-sensitive ones like proposal checklists, budget justifications, or closeout checklists — including one or two example outputs in the prompt can dramatically improve the result. This is sometimes called few-shot prompting. It is most useful when the format is unusual or when you need a specific style. It is less necessaryuseful when the task is well-known and you trust the model's defaults.

### 5.8 A Worked Example

A schematic of the seven components, applied to a real RA task:

> **Role:** You are a pre-award research administrator at the University of AI.
> **Context:** I need a one-page summary of NIH FOA RFA-XX-24-001 for engineering faculty who get many FOA alerts and need to assess fit quickly. UAI is a public R1 institution.
> **Instruction:** Extract and summarize the FOA along the dimensions below.
> **Input Data:** [FOA text attached]
> **Output Format:** Use headers for each section: Program Overview, Key Dates, Funding, Eligibility, Scientific Scope, Special Requirements, Review Criteria, Cost Share/Match Assessment, Red Flags, Recommended Next Steps. Keep [^cj17] to 1–1.5 pages. Use bullet points. Bold anything unusual or restrictive.
> **Constraints:** Do not paraphrase NIH jargon without translating it. Do not pad. If a section is not addressed in the FOA, say so explicitly.
> **Examples:** [attach a prior summary your office has used.]

This took roughly ten to fifteen minutes to write the first time, and will take about ninety seconds to reuse again. The full version of this example, with the actual output it produces, is in the FOA Example of Poor vs Well-Engineered Prompt supplement. [^mm18] [^bb19]

---

## 6. From Prompt Engineering to Context Engineering

So far we have treated prompt engineering as a self-contained skill: write better prompts, get better outputs. That framing is correct as far as it goes, but it is incomplete. As AI tools have evolved, a broader skill has come into focus, one that the field is now calling context engineering. Anthropic's engineering team described it in September 2025 as the "natural progression" of prompt engineering. The term matters because it changes what we should pay attention to.

### 6.1 The Context Window: The AI's Page Limit

Every AI model has a context window. Think of it as the model's working memory: the total amount of information it can hold and process at any given moment. Everything the AI "knows" during your interaction must fit inside this window. When the window is full, older information starts getting pushed out or compressed. The model does not have a filing cabinet it can reach into. If something is not in the context window right now, it effectively does not exist. Remember that any absences in relevant information are subject to the AI's guesswork.

If you have ever written an NSF project description, you already understand this type ofe constraint. You have fifteen pages. Everything that matters — intellectual merit, broader impacts, project objectives, significance, methodology, preliminary data, results from prior NSF support, and what benefits may result — has to fit. You cannot attach an appendix labeled everything the reviewer might want to know. You have to choose what earns its space. The context window works the same way.

### 6.2 Three Things Compete for the Window

That limited space is filled with three kinds of information.

**First, instructions.** This is the set of rules and guidance that tells the model how to behave. Think of it as the RFP requirements: the solicitation tells you what the sponsor wants, what format to use, what to include and exclude. In AI terms, instructions include the system prompt (written by the tool's developers), any custom instructions you have set ("I work at a public research university; our F&A rate is 56% MTDC" [^cj20]), behavioral rules, and examples of desired output.

**Second, relevant information.** This is the knowledge the model needs to do its job for your specific task. Think of it as the supporting documents you would assemble for a proposal: the project narrative, the PI's biosketch, the letters of support. In AI terms, this might include uploaded documents (a RFP, a budget template, the sponsor's guidelines, data retrieved from a database, institutional policies, or summaries of earlier conversations.

**Third, the conversation itself.** Your current message, the model's response, your follow-up, its next response, and so on. Think of it as the back-and-forth with a grant officer: each exchange is intended to adds clarification, but the longer it goes, the harder it is to keep track of what has been said. As the conversation grows, this part of the window expands and can crowd out the instructions and the documents that started the session. This is why AI tools sometimes seem to "forget" earlier context in a long thread.

The total capacity is finite. Everything competes for the same space. And the quality of what the AI produces depends directly on what is in that window. Give it the right instructions, the right information, and a focused conversation, and it performs remarkably well. Give it vague instructions, irrelevant documents, and a sprawling chat history, and its performance degrades — even if the underlying model is exactly the same. Just like a proposal: the same PI with the same science will get different review scores depending on how well the narrative is assembled within the page limit.

### 6.3 Three Disciplines, One Window

Each part of the context window has its own emerging discipline.

**Prompt engineering** optimizes the instructions: how you phrase the request and define the task. It is the skill that mattered most in the early days of AI chat tools, when interactions were single-turn and the wording of your request was the main lever.

**Context engineering** optimizes the information: what documents, data, and knowledge the model can see. It asks: what is the minimum set of materials the model needs to do this task well, without overloading the window with noise? It is the difference between uploading the entire Uniform Guidance and uploading the three sections on cost allowability that are relevant to the question. [^cj21] [^cj22]

**Conversation management** optimizes the interaction: when to continue, when to reset, how to keep the window balanced. It is the discipline that recognizes when a thread has gone on long enough that the model is losing track of the original instructions and decides to start a fresh conversation with a clean summary rather than course-correct a degraded one.

| Prompt Engineering | Context Engineering | Conversation Management |
|---|---|---|
| Optimizes the instructions: how you phrase the request and define the task. | Optimizes the information: what documents, data, and knowledge the model can see. | Optimizes the interaction: when to continue, when to reset, how to keep the window balanced. |
| Like writing to a sponsor's RFP requirements. | Like assembling the supporting documents for a proposal. | Like managing a back-and-forth with a grant officer. |

### 6.4 Why This Matters for Research Administration

Research administrators already think in all three disciplines, even without these names. When you onboard a new grants specialist, you do not just hand them a task and walk away. You give them the institutional policies, the sponsor guidelines, the templates, the historical examples, and the procedures manual. You build an environment that makes them effective. Then you manage the ongoing relationship: checking in, course-correcting, knowing when to step back, and when to intervene.

Working with AI is the same. Instead of asking "can you draft a budget justification?" and hoping the model guesses your sponsor's requirements, you set up custom instructions with your institutional context (prompt engineering), upload the RFP and sponsor's guidelines (context engineering), and manage the interaction strategically (conversation management).

This reframing changes how one arrives at the benefits of AI. who benefits from AI. When prompt engineering was a more distinct skill, one accessed the rewards of AI by crafting strong prompts. Now that communication with AI tools is more wholistic, one reaps the benefits of AI by managing all three disciplines. The individual or team who can effectively organize information and manage processes is far more likely to have success implementing AI tools. Prompt engineering rewarded the person who was best at talking to the machine. Context engineering and conversation management reward the person, team, or institution that is best at organizing information and managing processes. Think about what makes a great pre-award administrator: it is not eloquent emails to the sponsor. It is knowing which documents to assemble, what information to surface at what moment, and when a conversation needs to be reset with a clean summary. Those are exactly the skills that make someone effective with AI.

### 6.5 What This Looks Like in Practice

Four habits, all available to any RA who is not a developer.

- **Build your institutional context once, then reuse it.** Set up custom instructions, your institution type, the compliance frameworks you work under, and your preferred output style. This is like building a proposal template library: you invest the time once, and every future interaction starts from a stronger position.
- **Upload strategically, not exhaustively.** When you need the AI to review a budget against an RFP, upload the specific sections of the RFP that address cost allowability — not the entire 200-page solicitation. Overloading the AI is like attaching every policy in your shared drive to an audit response: the important information gets buried.
- **Know when to start a new conversation.** If you have been going back and forth for dozens of messages and the quality is slipping, the conversation itself may be crowding out the instructions and documents the model needs. Starting fresh and re-uploading the key materials often improves results dramatically. It is the same instinct that tells you when an email chain with a subrecipient has gotten too tangled and it is time to schedule a call.
- **Curate what the AI does not see.** Context engineering is not just about adding more information. It is about knowing what to leave out. Just as you would not include preliminary data from an unrelated project in a proposal, you should not feed the AI documents that are tangentially relevant but ultimately noise. Choosing the right three pages from a 200-page manual is itself an act of context engineering.

### 6.6 Reusable Workflows: Build Once, Use Everywhere

Once you have figured out the right combination of instructions, documents, and interaction patterns for a particular task, the natural next step is to save it. This is where reusable AI workflows come in, and it is where context engineering starts to look less like an individual skill and more like an institutional capability.

A workflow packages the context engineering decisions you have already made: which documents to provide, what instructions to include, what output format to expect, and how tasks chain together. Instead of each person in your office independently figuring out how to get the AI to extract deadlines from an FOA, you build the workflow once, test it, and share it. The next person just supplies the document and runs it. The prompt engineering, context engineering, and conversation management are baked in.

Tools like Promptulus and Vandalizer, developed by the AI for Research Administration team, are designed around this principle: letting RAs encode their institutional knowledge into reusable workflows that deliver consistent results regardless of who runs them. Think of it as the difference between a one-off email to a sponsor and a standard operating procedure. Both get the job done, but the SOP ensures consistency, reduces errors, and means a new staff member can execute the process on day one. [^mm23] [^bb24] [^td25]

---

## 7. The Prompt Engineering Cycle

Prompt engineering is iterative. Even good prompts rarely emerge fully formed on the first try, and the goal is not to write the perfect prompt up front. The goal is to converge on something reliable through a few quick rounds of refinement.

**Infographic placeholder.** The Prompt Engineering Cycle: Draft → Test → Refine → Use → Refine → Use. Show as a loop, not a line. [^mm26]

The basic cycle has five moves.

1. **Draft.** Assemble the components from Section 5: role, context, instruction, input, output format, constraints, examples. Do not try to perfect it.
2. **Test.** Run the prompt on a real or representative input. Read the output critically.
3. **Refine.** Identify the gap between what the prompt produced and what you needed. Adjust one element at a time — often the format or the constraints, sometimes the context. Do not rewrite from scratch unless the output is genuinely off topic.
4. **Use.** Once the prompt produces something you can use with only light editing, save it. Give it a name. Note what it is for.
5. **Refine again, with use.** [^td27] Real usage will surface edge cases and weaknesses. The third or fourth time you reuse a prompt, you will probably tweak it again. That is healthy, not a sign of failure.

A good prompt is a working document, not a fixed artifact.

---

## 8. Strategies for Refining Outputs

Three strategies pay off particularly well in research administration.

### 8.1 Creating and Using an Agent

Many AI tools now allow you to create a persistent "agent" — sometimes called a custom GPT, a project, or a workspace — with a fixed set of instructions and uploaded reference documents. For an research administration office, this is enormously useful. You can stand up [^cj28] an agent for NIH proposal review, another for DOE budget compliance, another for post-award closeout, each pre-loaded with the relevant regulations, institutional rates, and templates. The agent saves you the work of re-supplying context every time. It also enforces consistency across the office: everyone interacting with the NIH proposal review agent gets answers grounded in the same materials.

### 8.2 Using a Tool Like Promptulus

> **Note for Dashiell:** Confirm if/where Promptulus will be hosted for this course and what URL learners should be sent to. Decide whether the in-module exercise uses Promptulus directly or a hosted demo version.

Tools like Promptulus take this further by codifying common research administration prompts into reusable templates. [^td29] [^td30] Rather than starting from a blank prompt every time, the user supplies the variable inputs (the RFP, the award, the sponsor) and the template handles the rest. This shifts the work from prompt-writing to prompt-selecting, which is faster and produces more consistent results.

### 8.3 Managing Limitations and Verifying Accuracy

Even the best prompt does not eliminate the need to verify. AI models sometimes hallucinate — confidently producing citations to regulations that do not exist, or numbers that do not check out. The defense is structural, not vigilant. Build verification into the prompt itself: ask for citations after each claim, ask for the math to be shown, ask for explicit flags when the model is uncertain. Then spot-check those elements before you use the output. The trust-but-verify principle is easier to apply when yourthe prompt produces has given you specific things to verify.

A short list of what to verify, every time, in research administration outputs:

- Regulatory citations (do they exist? do they say what the model says they say?)
- Numerical calculations (do the totals add up? are F&A calculations correct?)
- Sponsor-specific claims (does the RFP actually say that?)
- Names, dates, and identifiers (these are common hallucination sites)
- Anything that would be embarrassing or compliance-relevant if wrong

---

## 9. Quick Check for Understanding

Two short exercises to close the module.

### 9.1 Exercise 1: Try Promptulus

Pick a task from your current workload — an RFP summary, a budget or award review, a closeout email, anything where you would normally start from a blank message box — and use Promptulus to refine your prompt before using in an AI tool. Compare the output of a Promptulus assisted prompt to what you would have produced without it. Note the time difference and any quality difference.

### 9.2 Exercise 2: Bert's Puzzles [^mm31] [^bb32] [^td33]

Solve a short series of RA puzzles in two passes. The first pass: no prompting strategy at all, just type what comes naturally. The second pass: apply the components from Section 5. Compare the outputs. The point is not to embarrass anyone with the first pass; it is to make the second-pass improvement vivid.

---

## 10. Where to Go from Here

A short recap. Prompt engineering is the discipline of writing good instructions. Context engineering is the discipline of assembling the right information. Conversation management is the discipline of keeping the interaction focused. All three matter, and all three are extensions of skills research administrators already have. The shift from linguistic craftsmanship to systems thinking should feel familiar: research administration has always been about making sure the right information is in the right place at the right time so that decisions can be made well.

---

## Appendix A: Source Materials and Supplements [^td34] [^td35]

The following supporting documents accompany this module and should be made available to learners as reference materials and as worked examples:

- **Examples of Poor RA Prompts** — ten short examples illustrating the failure patterns from Section 4.
- **Examples of Typical RA Prompts** — three fully developed real-world RA prompts (PI email, award terms summary, closeout email) used in Section 2.
- **FOA Example of Poor vs Well-Engineered Prompt** — the worked example referenced in Section 5.
- **Personnel Costs Justification Example of Poor vs Well-Engineered Prompt** — additional worked example.
- **Unallowable Costs Example of Poor vs Well-Engineered Prompt** — additional worked example, with regulatory citations.
- **Your AI Has a Page Limit (AI4RA blog post)** — the long-form treatment of the material in Section 6.

---

## Appendix B: References [^mm36]

- Anthropic Engineering Team. (September 2025). Context engineering for AI agents. *Anthropic Engineering Blog.*
- Atreja, S., Ashkinaze, J., Li, L., Mendelsohn, J., & Hemphill, L. (2024). Prompt design matters for computational social science tasks but in unpredictable ways. arXiv:2406.11980.
- Bens, A., Harmon, D., Harris, R., Henderson, T. (2023). AI in Research Administration: Unlocking Efficiency and Innovation. National Council of University Research Administrator Webinar
- Your AI has a page limit: Building the environment that leads to success. AI for Research Administration. TO DO: LINK NEEDED
- Harmon, D., Kirk, M., Bens, A., Bjorndal, E. (2024). Surfing the AI Wave: Working Smarter Not Harder. National Council of University Research Administrators Financial Research Administration Conference, Honolulu, HI.
- Karpathy, A. (2025). Public remarks on context engineering, summer 2025.
- Lütke, T. (2025). Public remarks on context engineering, summer 2025.
- Summers, N., Strubles, J. (2026). AI Literacy. University of Idaho Bridge. https://uidaho.bridgeapp.com/learner/courses/9c70ffa9/enroll

---

## Drafting Notes (to be removed before publication)

- Section 5 ("Components of an Effective Prompt") was the section assigned to Bert in the original outline. The seven-component framework is consolidated from the worked examples in the supporting documents (especially the FOA, Personnel, and Unallowable Costs examples), which all use a recognizable role/context/instruction/input/format/constraints structure.
- Section 6 is new relative to the original outline. It draws primarily on the Your AI Has a Page Limit blog post and the framing in the Bulk From Prompt Engineering to Context Engineering email. The original outline did not include context engineering; given the user's note, this section is essential.
- The Promptulus demo and the puzzle exercise both depend on resolving the hosting question with RCDS (flagged in 8.2 and in the original outline).
- The "Prompt Engineering Cycle" infographic referenced in Section 7 still needs to be designed.
- Atreja et al. (2024) is the only empirical citation; if we want more grounding in the prompt-engineering literature, candidates include White et al. (2023) on prompt patterns and Wei et al. (2022) on chain-of-thought, both already cited in the Atreja paper's references.

---

## Reviewer Comments

[^cj1]: **CJ1:** What about other considerations i.e is this the right tool. Maybe we add "For appropriate AI use cases..."
[^cj2]: **CJ2:** security? transparency? I'm not sure if it's the most important thing. It may be the most important skill. Or we can call it a critical skill.
[^cj3]: **CJ3:** Is this subsection necessary? I think there's an opportunity to synthesize the details in this section with those in the 1.1 introduction paragraph. Maybe we make that subsection "1.1 The AI Communication Challenge" and let it be implied that it's an intro.
[^cj4]: **CJ4:** is this an example of a more structure tool or more structure implementation?
[^cj5]: **CJ5:** I'm not sure that this detail helps make the distinction between unstructured and structured prompts. Isn't it applicable to both cases?
[^cj6]: **CJ6:** I'm a bit confused which approach is being referred to here.
[^cj7]: **CJ7:** is this describing what the AI might say?
[^cj8]: **CJ8:** A rushed process.
[^cj9]: **CJ9:** Absent context
[^cj10]: **CJ10:** An unidentified audience.
[^td11]: **TD11:** Update language to say "look for these kinds of things" ie make it more diagnostic
[^cj12]: **CJ12:** Some common pitfalls in prompt engineering.
[^cj13]: **CJ13:** Your prompt is vaguely applicable to any organization.
[^cj14]: **CJ14:** suggesting this because i thin vagueness is what we are trying to ID here.
[^cj15]: **CJ15:** It is difficult to verify whether the output is compliant or accurate.
[^cj16]: **CJ16:** This explanation offers a lot of clarity to me and I really like it. It makes me think that this section should go before the 4.2 and 4.3 so that when you refer to verification difficulties in 4.3, I know exactly what you're talking about.
[^cj17]: **CJ17:** Restrict the summary to?
[^mm18]: **MM18:** Will this actually be a thing?
[^bb19]: **BB19:** Do you think it's worth making it a thing? I think this was a placeholder for one of your examples you shared with me.
[^cj20]: **CJ20:** Is this an instruction or relevant information to effectively satisfy instructions?
[^cj21]: **CJ21:** I think one of the challenging aspects of these terms is that prompt engineering, as we describe it above, still involves providing relevant context for the AI to produce an effective output. Here, prompt engineering is described as the request for the task. It seems like the meaning of prompt engineering changes in an effort to make it distinct from context engineering. We should think about how to address this.
[^cj22]: **CJ22:** Should "prompt engineering" be revised to "prompt craft" or something like that?
[^mm23]: **MM23:** Do we want this? It seems like we are shamelessly promoting our tools.
[^bb24]: **BB24:** Good question for Dashiell: we could point to Vandalizer as one exampl, and perhaps mention others as well?
[^td25]: **TD25:** I agree this feels a little promotional. This is the first time in the document you mention specific tools, besides Promptulus, and of course its ours. However, I think its natural we promote Vandalizer here, especially considering that it is open source. Vandalizer is the only AI tool custom built for RAs which fundamentally incorporates all of the information you mention above to solve RA specific tasks. Not mentioning it, to me, feels like an injustice to the reader, especially considering we're not asking them to purchase anything. Maybe I'm biased but I feel like they will get higher quality outputs for these types of tasks using Vandalizer over any other LLM. I do think we could mention other tools here and describe how a workflow would look using them, but then reference Vandalizer as the best option for utilizing re-usable workflows. The important thing for this section is describing what a workflow is in practice: a re-usable series of prompting tasks which lead to a structured output. I also think this section could afford a graphic depicting what a workflow looks like from start to finish.
[^mm26]: **MM26:** Infographic needs created
[^td27]: **TD27:** Repeat/Iterate Steps 2-4 makes more sense to me
[^cj28]: **CJ28:** set up? establish?
[^td29]: **TD29:** You mention the idea of reusable templates a couple times throughout, however in your poor prompt test bullets, you mention a couple statements that somewhat suggest they shouldn't be re-usable (bullet 1 and 4). I think a statement on what makes a good template is necessary with an example template that includes brackets showing sections where the template would need to be edited. For example, "I need a [number of pages] summary of [sponsor guideline section] for [faculty department] faculty who get many FOA alerts and need to assess fit quickly." Maybe a section titled "How to create your own library" or something of that nature.
[^td30]: **TD30:** We have a prompt library in our new AI4RA Github repo that we could provide here as well.
[^mm31]: **MM31:** Bert will need to provide these
[^bb32]: **BB32:** Yes, this will depend in part on what is possible akin to Promptulus
[^td33]: **TD33:** Reverse engineering prompts. Add this to the public AI4RA github
[^td34]: **TD34:** Larger full course comment. We should include a vocabulary list from the course as whole thats sub divided by module.
[^td35]: **TD35:** We can probably use an LLM to extract key vocab and definitions.
[^mm36]: **MM36:** Verify. Are these correct? Do other references need added? Michele needs to add the OIT AI Literacy course citation.
