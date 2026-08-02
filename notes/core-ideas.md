# Core Ideas Across the Course

The kernel of each module. Not a summary. The load-bearing ideas that would be worth remembering a year later.

## Module 1: Introduction to AI

1. **AI is behavior inferred from data, not specified in advance.** You can approve the tool, the permitted uses, and the guardrails. You cannot approve the specific output. Assurance has to move from the tool to the processes around it.
2. **Crowd of amateurs.** LLMs are strong on consensus knowledge, common sense, drafting, and summarizing. They are weak on novel, contested, or specialist material. Asking twice is polling the same crowd twice, not verification.
3. **Three legs of assurance:** direct inspection, audit trail, validation. More AI autonomy shifts the weight from inspection to the other two.
4. **AI vs data science.** If you need precise, reproducible, auditable answers on structured data, reach for data science first. AI is for unstructured text, pattern recognition, and language generation, always with validation.
5. **AI Use Continuum:** process-critical, human-in-the-loop, output-driven. The core question is whether *how* the work was done matters, or only *what* the output is.

## Module 2: AI Ethics

1. **Ethics is the practice of asking the right questions, not memorizing principles.** The hard part is holding tensions between principles that pull in different directions.
2. **Descriptive vs. normative.** You cannot derive an "ought" from an "is" (naturalistic fallacy). But "ought implies can": impossible duties do no normative work.
3. **Two methodologies.** Argument by analogy, challenged by identifying a relevant dissimilarity. Reflective equilibrium, iterating between gut reactions and principles until they cohere.
4. **Four guiding questions:** Who is made vulnerable? How can harm be minimized? Who benefits and how are benefits distributed? Can the adoption be reversed? Prefer reversibility under uncertainty.
5. **Three collective action structures:** tragedy of the commons (regulation, quota), prisoner's dilemma (binding agreement, transparency), stag hunt (trust, visible commitment). The structure, not intentions, does much of the work.
6. **Individual ethics is not collective ethics.** What is rational for one administrator can be corrosive if adopted by everyone.

## Module 3: Prompt Development

1. **Prompt quality determines output quality.** In research administration, fast and wrong is more dangerous than slower and right.
2. **Seven components of an effective prompt:** Role, Context, Instruction, Input Data, Output Format, Constraints, Examples.
3. **The context window is the AI's page limit.** Three things compete for the same finite space: instructions, relevant information, and the conversation itself.
4. **Three disciplines, one window.** Prompt engineering shapes the instructions. Context engineering assembles the information. Conversation management keeps the interaction focused.
5. **Iterate:** Draft, Test, Refine, Use, Refine again. A good prompt is a working document.
6. **Build verification into the prompt.** Ask for citations, math, explicit uncertainty flags. You cannot verify what you did not specify.

## Module 4: Compliance and Governance

1. **Compliance Pyramid.** The most restrictive applicable guideline governs: institutional, sponsor, state, or federal. The pyramid works the same way for AI as for everything else in RA.
2. **Multi-level governance, no single anchor.** There is no comprehensive US federal AI law. States are leading. Sponsors (NSF, NIH, DOE) are building agency-specific frameworks. Institutions must fill the gaps.
3. **Embed AI controls in existing workflows.** Add disclosure questions to routing forms, DMPs, proposal attestations, and post-award setup. Do not build parallel systems.
4. **5W1H for policy design:** What, Why, Who, When, Where, How.
5. **Data classification drives tool choice.** PII, PHI, FERPA, export-controlled, IRB-protected, proprietary, and confidential data must be matched to an appropriate tier (public chatbot vs. private/approved tool vs. data science).
6. **Accountability practices.** Document when and how AI was used, keep a human in the loop for validation, and maintain an audit trail sufficient for reproducibility.
