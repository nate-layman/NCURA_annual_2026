# Module 1: Introduction to AI in Research Administration

**Course:** AI and Data Science for Research Administrators
**Module:** 1 of 5 [^cj1]
**Estimated Time:** 90–120 minutes

## Module Overview

In light of rapid innovation in the AI sector, there is an abundance of AI-related information circulating online, which can amount to overwhelming and sometimes even misleading discourse. This module provides credible, accessible information for Research Administrators to understand what AI is and how it can fit into Research Administration (RA) workflows. Module 1 lays the foundation for practicing responsible, beneficial AI implementation by guiding RAs to develop core skills to make informed judgements about AI usage, both for specific use cases and at scale.

Module 1 meets this broader objective through the following specific aims.

1. Define artificial intelligence and distinguish it from related terms (machine learning, natural language processing, etc.)
2. Recognize and refute common misconceptions about AI
3. Identify administrative and research processes where AI is likely to add value at relatively low cost
4. Categorize and identify AI tools for RA
5. Recognize how AI fits into broader technological and human-powered processes. [^cj2] [^cj3]

*insert sections*

---

## Section 1: What Is Artificial Intelligence? Overview and Key Terms

This section will provide official definitions of artificial intelligence, accessible explanations of what artificial intelligence is (and isn't),

### 1.1 Defining AI

Our definition and characterization of AI is based on the current Code of Laws of the United States of America 15 U.S.C. § 9401(3), which states: The term "artificial intelligence" means a machine-based system that can, for a given set of human-defined objectives, make predictions, recommendations or decisions influencing real or virtual environments. Artificial intelligence systems use machine and human-based inputs to:

- (A) perceive real and virtual environments;
- (B) abstract such perceptions into models through analysis in an automated manner; and
- (C) use model inference to formulate options for information or action.

The definition provided by the USC is correct, holistic, and ought to be upheld. However, this definition is also technical and can be unpacked to provide an accessible starting point for understanding the technologies that constitute artificial intelligence. An accessible, in-depth explanation of AI technologies be found in an NCURA-supported video, *What is AI (and what is isn't)*. [^cj4] In this video, Dan Harmon of the University of Illinois Urbana-Champaign offers a definition of AI and addresses some common misconceptions and conflations surrounding AI. While we encourage you to check out the video, we will also relay, unpack, and build off of some of his key points here.

**What is AI? (Harmon, 2025)**

- Artificial intelligence (AI) refers to machines or software systems that perform tasks that typically require human intelligence.
- AI machines can simulate human intelligence in a variety of ways, including but limited to understanding language, image recognition, making data-backed decisions (i.e driving cars), and generating content (videos, music, images, text).
- AI learns from data. The data that is used to inform AI machines is commonly referred to as training data. The training data fed to AI technologies is critical to AI decision making and overall performance.
- Recently, AI technologies have evolved to include generative AI, technologies that have the ability to generate new content from the training data that it has been given.

For the purposes of this course, AI can be thought of as any tool whose behavior is inferred using patterns learned from data, rather than specified in advance. The tool works out its own answer rather than being provided a set of rules to determine how to respond. This matters for research administration because behavior that isn't specified in advance can't be approved in advance. We can approve the tool, the permitted uses, and the guardrails, but never the specific output. Assurance therefore has to move from the tool to the processes around it.

### 1.2 AI is an Umbrella Term

The term "AI" encompasses a variety of specific technological processes, which can be performed between different types of AI tools (sometimes with overlap). One AI tool that has recently drawn a great deal of attention to the AI sector is the Large Language Model (LLM) such as GTP-4 (ChatGTP, Open AI) or Sonnet (Claude, Anthropic). LLMs interpret natural human language, then use patterns from learned data to generate a response that is likely to benefit the user. This technological technique is known as Natural Language Processing. Users interact with LLMs through an AI chatbot, a computer program that simulates a human conversation between the user and the LLM. [^cj5]

Despite the notoriety of the most commonly recognizable LLMs, it is important to keep in mind that these tools represent one of many types of AI technologies, performing some of the possible AI techniques. The table below features a more comprehensive overview of the AI techniques available to us through the broader array of AI technologies. [^cj6] [^cj7]

| AI Technique | Description | Example |
|---|---|---|
| Machine Learning (ML) | Systems that learn from data to make predictions or decisions | Credit scoring, fraud detection |
| Deep Learning (DL) | A subset of ML using layered neural networks | Image classification, speech recognition |
| Natural Language Processing (NLP) | Understanding and generating human language | Chatbots, document summarization |
| Image Recognition (IR) | Identifying objects or patterns in visual data | Facial recognition, medical imaging |
| Reinforcement Learning (RL) | Learning through trial and reward | Self-driving cars, game-playing AI |

### 1.3 Misconceptions Surrounding the term AI

AI technologies can do a lot, and with their rapid development, they are increasingly becoming a part of our day-to-day lives. As the interest surrounding AI increases, there are some points of confusion and conflation circulating through the public as we make sense of these technologies. While AI is an umbrella term, it is not all-encompassing, and there are some mischaracterizations of AI that we ought to address here.

**AI is NOT:**

- **Magic.** AI works through algorithms, data, and computation. AI operations are powered by technological infrastructure as well as monetary and natural resources. [^nl8] [^cj9] There is a great deal that goes into making AI work as it does, making it all the more crucial to think critically about effective and worthwhile implementation before putting AI tools to use.
- **Conscious.** AI technologies are inspired by the human brain (e.g., neural networks), but they do not replicate biological cognition. Human brains constantly rewire themselves in response to new experiences, while an AI model's weights are fixed once training ends. For an AI model, the external interventions that produce learning are deliberately facilitated. [^cj10] Further, AI tools neither think nor feel emotion the way people do, despite the ability of some AI technologies to simulate these behaviors.
- **Antagonistic to human creativity.** AI can generate original art, text, and music by using existing works as a reference. These capacities have led some to believe that AI stands as a substitute for human creativity. The relationship between human creativity and generative AI is far more nuanced, however. While AI can be used to substitute some of the production processes of human creation, human knowledge, creativity, and decision making play a crucial role in generating creative works with AI technologies. At its best, AI has demonstrated the power to enhance and inspire human creativity.
- **Perfect.** AI makes mistakes, including hallucinations (confidently stating false information), and can reflect biases present in its training data. AI is a powerful, inspiring tool, but like any other tool, its value strongly depends on its implementation.
- **One thing.** It is a conglomerate of technological techniques including machine learning, language processing, and pattern recognition.
- **A new concept.** People have imagined artificial minds for a very long time, from Talos in Greek myth onward. The methods behind today's tools are older than they look: least squares regression, the simplest form of neural network, dates to Gauss and Legendre around 1800. The term "artificial intelligence" was coined later, at a Dartmouth workshop in 1956, and the field has been quietly working its way into everyday systems ever since. Your institution has been using AI for years without calling it that, whether that be in the form of statistical analysis, machine learning, plagiarism detection, library search, or spam filtering. The question is rarely whether AI should be adopted. It more often which AI use cases require scrutiny.

### 1.4 A Human-Centric View of AI

Most AI tools are built to be used by people. From a human-centric perspective, AI is best understood as a system that infers the determined, stated, and/or implied goal(s) expressed by a person, generates an output that it determines will likely satisfy the goal(s), and returns something the person can evaluate. [^cj11] In its simplest form, the process is a loop:

> Human introduces goals via prompts or other input modes → AI infers implied and stated objectives and generates output → Human assesses the output and chooses to revise the output, revise the input to generate a different output, or accepts the output → repeat as needed

While the underlying technology has changed enormously, basic statistical methods to modern large language models, this basic pattern remains largely has been stable. People ask questions, give instructions, and iterate on results.

What has changed recently is how often human work appears in the loop. Agentic systems are given a goal and then run many cycles on their own, integrating tools and acting on intermediate results before returning anything for review. The loop is still there, but the human is no longer present at every revolution of the cycle.

*[Placeholder figure]* [^nl12]

That shift is important when it comes to assurance of the results. Assurance of the output comes from three places, and increasing AI autonomy shifts the weight between them. Direct inspection of the output tells you whether this particular result looks 'right'. An audit trail tells you how it was produced. Validation, running the tool on cases where you know the answer, tells you how often that particular task produces correct results I general, for that model. As AI tools take more steps on their own, direct inspection covers less of the work, so the other two have to carry more. [^cj13]

The use of agentic systems shifts the necessary conditions for sufficient assurance. This is because AI assurance is performed from three points of assessment: 1) direct inspection where the output is evaluated by the user(s), 2) an audit trail which outlines how the output was produced, and 3) validation, where users apply the tool on cases where the answers are already known to predict its effectiveness for prospective cases. When AI tools take more steps on their own, direct inspection carries less of the overall evaluation work. This means that the auditable trail and validation must carry more of the load.

### 1.4 A Useful Metaphor: The Crowd of Amateurs

A helpful [^cj14] way to think about interacting with Large Language Models and AI chatbots is to imagine posing your question to a crowd of a thousand broadly informed volunteers. The crowd considers your query, takes charge in surveying itself, and returns an answer that best represents their collective perspective. Since expertise among the crowd is diverse and not necessarily tailored to any specific domain, we'll call these volunteers our "crowd of amateurs." Thinking of general-use LLMs as your crowd of amateurs provides a useful metaphor to expect what interacting with these technologies will be like. The metaphor also offers a general rule of thumb for predicting when they will be both safe and beneficial.

Let's start with safety. RAs regularly handle highly sensitive, personally identifiable information. When this information is present in your inputs, you are effectively handing the information over to the crowd of amateurs. There are cases in which an LLM can be hosted in a secure environment, trusted by your institution, but in all other cases, it is fitting to imagine handing over this information to real strangers. The picture of what happens to your inputs in a commercially supported LLM is a complex one, but in an RA context, the important takeaway is that doing so compromises your institution's ownership of the information. [^cj15]

Once you verify that you can trust your crowd of amateurs with the necessary information to pose your query, you are ready to predict whether the crowd of amateurs will be a reliable resource to answer your query. There are some queries, such as those involving consensus knowledge, common sense, idea generation, and summarization of key information, that we could confidently outsource to our crowd of amateurs. Similarly, LLMs have demonstrated reliable effectiveness for these types of tasks.

There are other queries, however, for which we would not feel confident consulting with our crowd of amateurs for a dependable answer. Perhaps your query involves novel ideas, contended beliefs, or information that only domain-specific experts could make sense of. In these cases, we would take the time to seek out specialized perspectives. Similarly, it would likely be beneficial to turn to AI tools that are trained on that type of information, or in some cases, other modes of information processing that don't require artificial intelligence at all.

LLMs are good at tasks involving consensus knowledge, common sense, drafting, and summarizing. However, they tend to be unreliable when handling queries that require them to handle novel, contended, or specialist-level information unless they were specifically trained on them. When the models are wrong, they also tend to be wrong with the same level of confidence as when they are right. This metaphor also holds when explaining why asking the LLM a second time doesn't count as verification. Doing so would only amount to polling your Crowd of Amateurs twice.

This is a useful mental model for what interacting with AI is like. The tools are genuinely good at consensus knowledge, common sense, drafting, and summarizing. However, they tend to be unreliable on specialist questions unless they were specifically trained on them, on anything recent or contested, and on claims that haven't been widely repeated. When the models are wrong, they also tend to be wrong with the same level of confidence as when they are right. It also explains why simply asking a second time doesn't count as verification. You've just polled the same crowd twice.

And it explains why it's important to be cautious when sharing data. The crowd knows nothing about your specific award, protocol, or personnel file unless you hand it over first. That's what happens when you paste something into a chat window: you've given a thousand strangers a copy. Sometimes that's exactly what you want. Sometimes it's the thing your policy exists to prevent you from doing. It's why it's important to have guardrails in place to ensure security and to prevent your data from being used inappropriately by AI providers.

It also explains how AI models can be trained. Training a model is essentially equivalent to paying people some of the people in the crowd to yell their answers louder when you ask questions about a specific topic.

---

## Section 2: Articulating the Goals, the Limitations and Challenges for AI Supported Tasks in RA

Will the crowd of amateurs be a reliable resource for this query? Should I seek out a different AI tool? A data handling tool that doesn't involve artificial intelligence? In research administration, the answer to these questions isn't always instantly apparent, and in cases where the stakes are high, users will have to engage in some critical thinking to anticipate these answers.

Fortunately, there are reliable steps you can take to anticipate opportunities for safe, beneficial AI implementation. Sections 2–4 will walk you through these steps, beginning with your consideration and articulation of the prospective task(s) that can be augmented with AI, your goals for accomplishing these tasks, and the constraints and compliance requirements that must be honored and upheld as these tasks are executed.

### 1.1 What's the task at hand?

Before determining how you will implement AI tools into your administrative processes, it is worth taking the time to identify and articulate specific administrative tasks for which AI augmentation is likely to benefit your office and administration. This means that you are articulating exactly what you want the AI tool to do, which starts with a verb. In research administration, AI tools have demonstrated their ability to extract desired information from administrative documents, summarize key findings, compare similar documents, draft supplementary documents, and automate structured data tasks. See below for examples of these tasks being performed in an RA context.

- Extracting deadlines, eligibility requirements, and submission criteria from Requests for Applications (RFAs)
- Comparing versions of awards or proposals to identify changes
- Tracking compliance and financial-reporting requirements
- Parsing award language for policy mandates
- Automating effort-reporting templates and ROI calculators
- Building checklists for submission systems and post-award processes

Notice a pattern: these tasks are repetitive, structured, and data intensive. If something is done repeatedly in a methodical way using consistent inputs, AI can often be trained or prompted to do it, freeing RAs to focus on higher-judgment work.

Conversely, tasks requiring high strategic reasoning and complex human judgment are generally not suited for AI autonomy, even if AI can assist with pieces of the work.

### Section 2.2 Will AI Implementation be worth the trouble? Let's map it out.

While AI has demonstrated its ability to introduce real benefits to RA processes, it remains perfect, and AI can also introduce real compromises to RAs high standards for accurate results, reproducible processes, data security, and flexibility as AI-supported tasks integrate with other administrative processes.

There are some cases of AI implementation, such as those that violate institutional policy or sponsor compliance requirements, where the cost of AI implementation is clearly not worth its benefits. In many cases, however, weighing the costs against the benefits against the costs will require careful mapping. A task that is being considered for AI implementation can be mapped along two axes:

- **Institutional impact** — How significantly does this task affect research outcomes, compliance, or efficiency?
- **Ease of implementation** — How readily can AI be applied without major system changes or risk?

Articulating specific, achievable goals for the prospective AI-supported task, as well as the specific risks or processing adjustments implementations will require, will position you to map the use case more accurately and precisely. It is important to keep in mind that exercise in mental mapping is only the start in making judgements about the candidacy of a specific task or set of tasks for AI augmentation. It is by no means the final word.

### Section 2.3 AI Solutions vs. Data Science Solutions [^cj16] [^nl17]

When making preliminary judgements on whether AI implementation is likely to be worth pursuing, it is also important to keep in mind that there are always other solutions worth examining. Data Science Solutions are worth mentioning here, for data science techniques can be used to carry out data intensive tasks that AI tools are currently not suitable for. Data science and Artificial Intelligence can cross paths, so let's make some key distinctions between the two approaches...

|  | Data Science | AI / Machine Learning |
|---|---|---|
| **What it does** | Cleans and analyzes data using statistical and mathematical operations | Implements models to build and maintain applications that learn or predict |
| **Strengths** | Reproducible, precise, auditable | Flexible, handles unstructured data, scales well |
| **Weaknesses** | Rigid, requires clean and structured data | May hallucinate, non-deterministic, needs validation |
| **Best for** | Structured reporting, financial analysis, compliance checks | Pattern recognition, document analysis, language tasks |

**Rule of Thumb:** If your task requires a precise, reproducible, auditable answer from structured data, reach for data science tools first. If your task involves unstructured text, pattern recognition across many documents, or language generation, AI (with appropriate validation) may be the right fit.

When a research administrator encounters a technical problem, one may assume AI is the solution when instead, the most effective approach is a well-designed data science technique: a clean database query, a statistical model, or a structured Excel analysis. While AI solutions can be evaluated as worthy investments, data science solutions often remain worth investing in, including the labor and infrastructure necessary to facilitate them. The boundary between AI and data science solutions will remain in flux as AI tools become increasingly capable of reliably performing tasks formerly assigned to data science solutions.

With every advancement of AI, the boundary between AI and data science is shifting. AI is increasingly capable of performing data science tasks — but with less reliability and transparency than purpose-built statistical tools. For now, in contexts where auditability matters (as it often does in research administration), data science approaches remain preferable for structured, quantitative work.

---

## Section 3: AI Tools

Once a task is recognized as a strong candidate for AI augmentation, it is time to decide which AI tool(s) will be most effective in doing so. It helps to understand the broad categories of AI tools available to us and how they can fit into research administration processes. In an RA context, AI tools generally fall into three tiers: general-purpose AI assistants, specialized research tools, and RA-specific platforms.

> ⚠️ **A note on security before you proceed:** Always consult your institution's IT and data governance policies before using any AI tool with sponsored project data, personally identifiable information (PII), export-controlled information, or unpublished research data. Free tiers of general-purpose tools may use your inputs for model training. When in doubt, use only sanitized, non-sensitive data.

### 3.1 General-Purpose AI Assistants (LLM Chatbots)

These are the conversational AI tools most people encounter first. They are highly versatile and can handle a wide range of writing, summarization, and analysis tasks. The leading options as of 2026 are:

| Tool | Developer | Best Known For | RA Use Cases |
|---|---|---|---|
| ChatGPT | OpenAI | Versatility; largest user base | Drafting, brainstorming, summarization, policy Q&A |
| Claude | Anthropic | Long document handling; nuanced writing; fewer hallucinations on factual tasks | Policy analysis, document review, award letter drafting |
| Gemini | Google | Integration with Google Workspace; current web information | Literature synthesis, research using up-to-date sources |
| Microsoft Copilot | Microsoft | Deep integration with Microsoft 365 (Word, Excel, Outlook) | Proposal formatting, budget spreadsheets, email drafting |
| Perplexity | Perplexity AI | Cited, source-attributed answers; current information | Finding current funding opportunities, policy lookups |

**Key points for RAs:**

ChatGPT remains the most widely used general-purpose AI tool, with broad versatility across tasks. However, choosing the right tool depends on your specific goals and constraints. Independent tests have consistently shown Claude producing fewer hallucinations on factual tasks than ChatGPT — a meaningful difference in compliance or legal contexts where a confident wrong answer creates real problems. Microsoft Copilot is best suited for enterprise users and office professionals who rely heavily on Microsoft tools for daily work, while Perplexity still has an edge for time-sensitive topics and current events.

None of these tools are purpose-built for research administration. Systems like ChatGPT, Claude, and Gemini can support grant tasks such as summarizing reports, brainstorming language, or analyzing data, but they require close oversight and can produce incorrect or irrelevant information if not guided carefully.

### 3.2 Specialized Research and Document Tools

These tools are designed for specific phases of the research process — particularly literature discovery, document synthesis, and grant writing. They offer more domain-appropriate outputs than general chatbots.

| Tool | Primary Function | RA Relevance |
|---|---|---|
| Elicit | AI-powered literature review; queries across 138M+ scholarly sources | Identifying prior research for proposals; literature gap analysis |
| Semantic Scholar | NLP-powered academic search and discovery | Finding relevant prior work; tracking citation networks |
| Consensus | Citation-backed answers to research questions | Verifying factual claims; evidence synthesis |
| Instrumental | Grant discovery, tracking, and AI proposal drafting | Funding opportunity research; early-stage proposal drafts |
| Scite | Smart citation analysis; shows how papers are cited | Evaluating the strength of cited evidence |

AI research tools span all phases of the research lifecycle and are increasingly used to synthesize information at scale, reduce manual workload, and help researchers manage more data, more sources, and tighter timelines.

Tools like Instrumental — which introduced an AI drafting module in 2025 — are designed specifically for the grant cycle; they understand funder [^cj18] language, proposal formats, and the nuances of grant communication. However, AI cannot replace human work in crafting winning proposals, as topical expertise, human experience, and storytelling remain essential ingredients for a strong proposal.

### 3.3 RA-Specific Platforms: The Case of Vandalizer

The most relevant development in AI for research administrators is the emergence of platforms built specifically for RA workflows. The leading example is Vandalizer, developed at the University of Idaho through the NSF GRANTED program (Award #2427549), dedicated to reducing barriers and inequities within the research enterprise.

Vandalizer is an AI-powered document processing and knowledge extraction platform built specifically for research administrators. It automates repetitive, time-consuming tasks that use research documents — such as proposals and budgets — using flexible and reusable workflows to get accurate and reproducible results.

Through Vandalizer, administrators can create and apply AI-powered workflows that improve consistency and reliability across their document and data processing tasks. The platform was designed with four core principles in mind [^cj19] [^td20]: flexibility, accuracy, reproducibility, and security — all of which are essential in a sponsored programs context.

**Example tasks that Vandalizer can reliably execute:**

- Pull dates, budgets, and requirements from messy PDFs into clean, structured outputs
- Generate executive summaries tailored to specific grant guidelines
- Check a proposal against sponsor solicitation requirements and create a budget justification from a budget

Not only can Vandalizer perform these tasks discretely; with its "Workflow" function, Vandalizer has the power to combine tasks into pipelines where the output from one task becomes input for the next, creating reliable, scalable workflows.

The efficiency gains can be substantial. Research administrators often spend up to 20 minutes manually extracting critical information such as principal investigator details, budgets, timelines, and compliance conditions from a single award document — a task Vandalizer can accomplish with high accuracy in a fraction of the time.

🔗 Learn more and access a free trial: vandalizer.uidaho.edu
🔗 AI for Research Administration project: ai4ra.uidaho.edu

### 3.4 Prompts for Choosing the Right Tool

Selecting the best tool for an administrative task isn't always an easy choice. Use the set of prompts below to guide your selection.

| Question | Guidance |
|---|---|
| Is the data sensitive? | Use only institutionally approved tools for sensitive data; never input PII, export-controlled, or confidential data into free public tools |
| Does the task involve structured RA documents? | Consider RA-specific platforms like Vandalizer before general chatbots |
| Is current or cited information needed? | Use Perplexity, Elicit, or Semantic Scholar over general chatbots |
| Is the output going into a grant proposal? | Treat AI output as a first draft; always revise, verify, and apply human judgment |
| Does your institution have approved tools? | Check with your IT/compliance office — many institutions have enterprise licenses that provide better privacy protections than free tiers |

> 💡 **Bottom line:** Match the tool to the task, respect institutional data policies, and always validate outputs before acting on them.

---

## Section 4: Fitting AI into the Bigger Picture

Assigning AI tools to compatible tasks is a core skill in AI implementation, but in administrative contexts, human decision-making does not stop there. There is always a bigger picture to keep in mind; there are compliance requirements that must be honored; there are resource limitations that must be considered. Further, there are critical decisions to make regarding how AI tools will merge with human-powered processes. There are various degrees of autonomy that can be granted to AI tools, and these decisions can have significant impacts on compliance, impact, and reliability.

There is a core question to consider when deciding how much autonomy to outsource to AI tools: **Does it matter how the work was done, or only what the final output is?**

If the process must be transparent, auditable, and attributable to a named, accountable human — AI should not be the decision-maker. If only the correctness of the final output matters, AI may be a highly efficient tool.

### 4.1 The AI Use Continuum

AI use in RA can recognized as belonging to one of three tiers, each of which allows for various degrees of AI autonomy:

- **Tier 1: Process-critical tasks** require transparent, auditable, human-accountable steps. These tasks requrie reproducible tools (scripts, spreadsheets, structured queries) where each step is documented. AI should not replace human judgment here.
- **Tier 2: Human-in-the-loop tasks** allow AI to assist with select tasks — flagging issues, compiling information, generating summaries — while a trained professional reviews and approves the final decision.
- **Tier 3: Output-driven tasks** are those where only the correctness of the result matters. AI is well-suited here, though outputs should still be validated.

```
← PROCESS-CRITICAL          HUMAN-IN-THE-LOOP          OUTPUT-DRIVEN →
  Financial audits          Budget flag review          Boilerplate drafting
  Effort certification      Subrecipient risk summaries Document formatting
  Compliance reviews        Compliance summaries        Policy summarization
  Misconduct investigations First-pass analysis         Internal communications
```

> ⚠️ Regardless of which tier an AI use case belongs to, always validate AI outputs and monitor error rates.

### 4.2 Metaphors for AI Partnership

Often, effective [^cj21] AI use cases merge human and AI-powered work. These collaborations can take different forms, which can be easiest to recognize through metaphors for human collaboration. Below are five metaphors to frame how AI assistance can relate to human work in research administration.

**1) The AI is your Productivity Multiplier**

AI is a power tool that accelerates repetitive or mechanical tasks — like the difference between a hand saw and a table saw. It doesn't change the nature of the work; it changes the speed and scale at which it can be done.

- **Best for:** Formatting, conversion, and template generation
- **RA Examples:** Proposal preparation formatting, document conversion, internal summary generation
- **Caution:** Power tools require safety protocols; AI outputs still require review

**2) The AI is your Research Assistant**

AI functions as a search and synthesis engine for complex document sets — rapidly finding, connecting, and summarizing information across multiple sources in ways that would take a human hours or days.

- **Best for:** Extraction, cross-document comparison, and pattern identification
- **RA Examples:** FOA/RFA analysis, policy interpretation, comparing award language across sponsors
- **Caution:** AI may miss nuance or misattribute information; always verify key findings against source documents

**3) The AI is your Drafting Partner**

AI can generate structured text quickly — providing a starting point that a human then refines. It is far better at drafting than at finalizing, and it excels when given clear templates or examples.

- **Best for:** First drafts, templates, and structured outlines
- **RA Examples:** Boilerplate sections of grant applications, internal documentation, routine communications
- **Caution:** AI drafts require human editing for accuracy, tone, and institutional voice

**4) The AI is your Junior Analyst**

AI is like a very fast but inexperienced analyst. It can read large volumes of documents, summarize policies, draft text, and flag potential issues — but it lacks the institutional context and professional judgment of an experienced RA.

- **Best for:** First-pass analysis, initial drafts, preliminary reviews
- **RA Examples:** Budget reviews, subrecipient risk summaries, compliance flag identification
- **Caution:** Always have an experienced professional review the junior analyst's work before acting on it

**5) Despite the potential relationships above, the AI is a "black box" (use with caution)**

AI outputs are non-deterministic (the same prompt can produce different answers) and difficult to explain in a step-by-step, auditable way. This makes AI fundamentally unsuited for tasks where the institution needs to demonstrate exactly how a conclusion was reached. There are significant limitations to the audibility of AI-powered processes.

- **Avoid for:** Any task requiring human accountability, auditability, or legal defensibility
- **RA Examples:** Financial audits, effort certification, IRB determinations, conflict-of-interest decisions, misconduct investigations
- **Key Principle:** If you would need to explain every step of the process under audit, do not use AI as the decision-maker

---

## Module 1 Summary

| Concept | Key Takeaway |
|---|---|
| What is AI | A collection of techniques for pattern recognition, prediction, and language — not magic, not consciousness |
| AI in RA | Most valuable for repetitive, structured, data-intensive tasks; not for judgment-dependent or auditable processes |
| Myths | AI is not objective, not a job-eliminator, not one thing, and not new |
| AI vs. Data Science | Data science = precise and reproducible; AI = flexible but needs validation |
| The Core Question | Does the process matter, or only the output? |
| Mental Models | Junior analyst, productivity multiplier, document assistant, drafting partner, black box |

---

## Knowledge Check

Answer the following questions to test your understanding before moving to Module 2.

### Question 1 — Scenario Analysis

Your sponsored programs office manages a portfolio of 200 active awards from a mix of federal and private sponsors. Each award has unique financial reporting deadlines, progress report due dates, and closeout requirements scattered across award documents of varying length and format. A staff member currently reads each document manually and enters key dates into a shared calendar — a process that takes several hours per week and is prone to human error.

Answer all four parts below using concepts from this module:

- **Part A — Is this suitable for AI?** Is this task suitable for AI, a data science tool, or both? Justify your answer, and explain what makes it a good or poor fit. [^cj22]
- **Part B — Where on the continuum?** Where does this task fall on the AI use continuum (process-critical, human-in-the-loop, or output-driven)? Explain your reasoning, and describe what human oversight should look like.
- **Part C — Which mental model(s) apply?** Identify one or two mental models from Section 7 that best describe how AI should function in this workflow. Explain why each applies.
- **Part D — Which tools would you use?** From the tool categories described in Section 5, which specific tool or tool type would you recommend for this task? Consider both general-purpose and RA-specific options, and note any data security considerations that apply.

### Question 2 — Match the Technique to the Description

Match each AI technique on the left to its correct description on the right.

| Technique | Description |
|---|---|
| A. Machine Learning | 1. Identifying objects or patterns in photos or scans |
| B. Natural Language Processing | 2. A system that learns from past data to make predictions or recommendations |
| C. Deep Learning | 3. Understanding and generating human language in text or speech |
| D. Image Recognition | 4. A layered neural network approach used for complex tasks like voice recognition |
| E. Reinforcement Learning | 5. Learning through trial-and-error using a reward signal |

*(Answers: A–2, B–3, C–4, D–1, E–5)*

### Question 3 — Fact or Myth?

For each statement, decide whether it is a Fact or a Myth, and briefly explain your reasoning.

| Statement | Fact or Myth? |
|---|---|
| AI and Machine Learning are interchangeable terms. |  |
| AI outputs can reflect bias from the data used to train them. |  |
| Artificial General Intelligence (AGI) is widely deployed in enterprise software today. |  |
| AI is designed to work alongside humans, not fully replace them. |  |
| If an AI system uses a neural network, it must be unbiased because math is objective. |  |

*(Answers: Myth, Fact, Myth, Fact, Myth)*

### Question 4 — In Your Own Words

In your own words, what is the difference between AI and Machine Learning?

### Question 5 — Applying the Continuum

Give two examples of RA tasks that belong on the "process-critical" end of the AI use continuum, and explain why.

### Question 6 — Applying Mental Models

A colleague wants to use an AI chatbot to certify effort reports because "it's faster." Which mental model best describes the risk here, and what would you tell them?

### Question 7 — AI or Data Science?

Your office receives 50 RFAs per year and spends significant time extracting eligibility requirements. Is this an AI task, a data science task, or both? Justify your answer.

### Question 8 — Reflection

Name one AI myth that surprised you and explain why it matters for research administrators.

---

## Additional Resources

- 🔗 [What is AI (and what it isn't) — NCURA](https://www.youtube.com/watch?v=-Elht3Imckk)
- 🔗 [AI Tools for Research Administration — NCURA](https://www.youtube.com/watch?v=iKRtA5DoRUg)
- 🔗 [Debunking 10 Common Misconceptions about AI — 365 Data Science](https://www.youtube.com/watch?v=zjeKSAsaSoA)
- 🔗 [Top 5 AI Myths — IBM](https://www.youtube.com/watch?v=-dAmqHFWzyg)
- 🔗 [Machine Learning Stir the Pile — XKCD Comic](https://xkcd.com/1838/)

Proceed to Module 2 when you are ready.

---

## Reviewer Comments

[^cj1]: **CJ1:** 1 of 4?
[^cj2]: **CJ2:** slightly revised the ordering and articulation of our specific aims.
[^cj3]: **CJ3:** most notably, I replaced "Differentiate between AI tasks and data science tasks" with "Categorize and identify AI tools for RA" because the former is a sub-aim of specific aim #3 and the latter was not represented.
[^cj4]: **CJ4:** when we figure out our mode of communication, we can then decide how to property cite this.
[^cj5]: **CJ5:** revised our description of LLM so that it is more aligned with our broader definition of AI. @Layman, Nathan (nlayman@uidaho.edu), please revise as you see fit.
[^cj6]: **CJ6:** how do we articulate that our audience does not need to develop an in-depth understanding of these techniques to make informed decisions about responsible and effective AI use? I worry that dropping this table could leave our audience feeling more overwhelmed than informed.
[^cj7]: **CJ7:** Should I revise the final sentence to something like "One does not need to developing an in-depth understanding of all the possible AI techniques in order to begin making informed decisions about AI implementation. Still, to demonstrate the broader possibilities of current AI technologies, we will outline some of the core AI techniques in the table below."
[^nl8]: **NL8:** I think we're bleeding into an entirely different topic here.
[^cj9]: **CJ9:** Is this entirely different? Let's chat more in our next meeting.
[^cj10]: **CJ10:** Please revise as you see fit. I feel that I am likely missing some nuance here.
[^cj11]: **CJ11:** did some slight revision on this description. Can I get a check from @Layman, Nathan (nlayman@uidaho.edu) and/or @Tyler, Dashiell (dashiellt@uidaho.edu)?
[^nl12]: **NL12:** Placeholder figure. I know it's not 100% yet.
[^cj13]: **CJ13:** Tried to revise to improve clarity and flow of ideas. See attempt below.
[^cj14]: **CJ14:** heavily revised crowed of volunteers section. Please review.
[^cj15]: **CJ15:** need help ironing out this paragraph but this represents my understanding of AI security in RA as it applies to this metaphor.
[^cj16]: **CJ16:** should we talk about having data scientists on staff/available? While AI solutions can be a worthwhile investments, other solutions remain worth investing in.
[^nl17]: **NL17:** Yes likely. And I like while AI solutions can be worthwhile investments, ...
[^cj18]: **CJ18:** sponsor?
[^cj19]: **CJ19:** we could link to our 4 pillars BP
[^td20]: **TD20:** The Four Pillars of AI4RA: A Foundational Framework – Artificial Intelligence for Research Administration
[^cj21]: **CJ21:** refer back to the crowd of amateurs.
[^cj22]: **CJ22:** most suitable for the task at hand.
