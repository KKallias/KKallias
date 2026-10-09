# Hi, I'm Konstantinos Kallias 👋

I am transitioning into **AI Automation Engineering**, building practical workflows that connect AI models with business processes and everyday tools.

My background in talent acquisition, operations, sales development, and data analysis helps me approach automation from both sides: understanding the real workflow first, then designing a clear and useful technical solution.

## Featured capstone

### [Scout Signal](https://github.com/KKallias/scout-signal)

**Football scouting research with reusable player profiles and human review.**

I built Scout Signal to explore how AI can help researchers collect player information, revisit earlier findings and check what has changed. It accepts pasted text or a Transfermarkt link, creates a concise profile and automatically stores valid research in Pinecone. Decision-makers can optionally save players to a Google Sheets review shortlist.

A separate retrieval workflow combines stored research with fresh searches for questions about current profiles or changes. The project demonstrates workflow orchestration, AI tool integration, vector retrieval and a clear separation between research storage and the human decision to shortlist a player.

**Built with:** n8n, OpenAI, SerpApi, Pinecone and Google Sheets.

**Status:** tested prototype with documented execution screenshots. Outputs require source checks and human judgement; broader evaluation remains future work.

[View project](https://github.com/KKallias/scout-signal) · [Execution evidence](https://github.com/KKallias/scout-signal#demonstrated-execution) · [Setup guide](https://github.com/KKallias/scout-signal#setup)

## Current focus

I am currently learning and building with:

`n8n` · `OpenAI API` · `AI Agents` · `RAG` · `Embeddings` · `Vector Databases` · `Pinecone` · `SerpApi` · `Structured Outputs` · `Gmail Automation` · `Google Sheets` · `Workflow Testing`

My focus is on:

* Designing complete AI automation workflows
* Connecting AI models with business tools and data sources
* Building knowledge assistants with retrieval-augmented generation
* Creating structured, testable, and maintainable automations
* Applying automation to recruitment, operations, and customer communication

## More AI automation projects

### [Recruitment Knowledge & Feedback Assistant](https://github.com/KKallias/recruitment-knowledge-feedback-assistant)

An n8n and OpenAI RAG prototype for retrieving answers from a controlled knowledge base of recruitment policies. It uses document ingestion, recursive text splitting, embeddings, Pinecone vector storage, and retrieval through an AI agent.

This project connects my Talent Acquisition experience with my transition into AI Automation Engineering.

### [Sales Handoff & Playbook Copilot](https://github.com/KKallias/sales-handoff-playbook-copilot)

An n8n RAG prototype with two workflows that ingests a fictional sales playbook, retrieves relevant guidance from Pinecone, and converts discovery notes into a structured handoff for human review.

The project demonstrates structured extraction, embeddings, vector retrieval, grounded generation, safeguards against prompt injection, and a clear separation between customer facts, company guidance, and AI suggestions.

### [AI Email Triage and Response Assistant](https://github.com/KKallias/ai-email-triage-n8n)

An n8n workflow that receives Gmail messages, uses OpenAI to extract structured information, logs the results in Google Sheets, decides whether a reply is required, generates a response, and sends it through Gmail.

The workflow demonstrates AI analysis, structured outputs, conditional routing, application integrations, and workflow testing.

## Explore the builds

Each project includes an n8n workflow export. Start with the setup instructions and check the current validation status before running it.

| Project | Workflow export | Setup and validation |
| --- | --- | --- |
| **Scout Signal** | [Ingestion](https://github.com/KKallias/scout-signal/blob/main/workflows/ScoutSignal_Ingestion_Output.json) · [Retrieval](https://github.com/KKallias/scout-signal/blob/main/workflows/ScoutSignal_Retrieval_Output.json) | [Setup and execution evidence](https://github.com/KKallias/scout-signal#setup). Tested capstone prototype supporting human decisions; broader evaluation remains future work. |
| Recruitment assistant | [Policy ingestion and question answering](https://github.com/KKallias/recruitment-knowledge-feedback-assistant/blob/main/workflows/01-upload-recruitment-policies-02-policy-assistant.json) | [Import and first test](https://github.com/KKallias/recruitment-knowledge-feedback-assistant#import-and-first-test). RAG foundation implemented; retrieval quality, citations, and abstention still need evaluation. |
| Sales handoff copilot | [Ingestion](https://github.com/KKallias/sales-handoff-playbook-copilot/blob/main/workflows/ingestion.json) · [Retrieval and handoff](https://github.com/KKallias/sales-handoff-playbook-copilot/blob/main/workflows/retrieval.json) | [Run the prototype](https://github.com/KKallias/sales-handoff-playbook-copilot#run-the-prototype). Prototype execution is documented; the evaluation plan covers grounding, commitments, and prompt injection. |
| Email triage assistant | [Email triage and response](https://github.com/KKallias/ai-email-triage-n8n/blob/main/workflow/ai_email_triage_response.json) | [Setup](https://github.com/KKallias/ai-email-triage-n8n#setup) · [Testing](https://github.com/KKallias/ai-email-triage-n8n#testing). Published export passed static checks; live validation remains a setup step. |

## Learning approach

I learn by building real portfolio projects and documenting the process clearly:

**learn → build → test → document → improve**

I am currently developing stronger skills in retrieval quality, grounded AI responses, workflow reliability, error handling, evaluation, and automation design for production environments.

## Connect

[LinkedIn](https://www.linkedin.com/in/konstantinoskallias/) · [GitHub](https://github.com/KKallias)
