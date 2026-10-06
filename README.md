# Hi, I'm Konstantinos Kallias 👋

I am transitioning into **AI Automation Engineering**, building practical workflows that connect AI models with business processes and everyday tools.

My background in talent acquisition, operations, sales development, and data analysis helps me approach automation from both sides: understanding the real workflow first, then designing a clear and useful technical solution.

## Current focus

I am currently learning and building with:

`n8n` · `OpenAI API` · `AI Agents` · `RAG` · `Embeddings` · `Vector Databases` · `Pinecone` · `Structured Outputs` · `Gmail Automation` · `Google Sheets` · `Workflow Testing`

My focus is on:

- Designing end-to-end AI automation workflows
- Connecting AI models with business tools and data sources
- Building knowledge assistants with retrieval-augmented generation
- Creating structured, testable, and maintainable automations
- Applying automation to recruitment, operations, and customer communication

## AI Automation projects

### [Recruitment Knowledge & Feedback Assistant](https://github.com/KKallias/recruitment-knowledge-feedback-assistant)

An n8n and OpenAI RAG prototype for retrieving answers from a controlled recruitment-policy knowledge base. It uses document ingestion, recursive text splitting, embeddings, Pinecone vector storage, and AI-agent retrieval.

This project connects my Talent Acquisition experience with my transition into AI Automation Engineering.

### [Sales Handoff & Playbook Copilot](https://github.com/KKallias/sales-handoff-playbook-copilot)

A two-workflow n8n RAG prototype that ingests a fictional sales playbook, retrieves relevant guidance from Pinecone, and converts discovery notes into a structured handoff for human review.

The project demonstrates structured extraction, embeddings, vector retrieval, grounded generation, prompt-injection safeguards, and a clear separation between customer facts, company guidance, and AI suggestions.

### [AI Email Triage and Response Assistant](https://github.com/KKallias/ai-email-triage-n8n)

An n8n workflow that receives Gmail messages, uses OpenAI to extract structured information, logs the results in Google Sheets, decides whether a reply is required, generates a response, and sends it through Gmail.

The workflow demonstrates AI analysis, structured outputs, conditional routing, application integrations, and workflow testing.

## Explore the builds

Each project includes an n8n workflow export. Start with the setup instructions and check the current validation status before running it.

| Project | Workflow export | Setup and validation |
| --- | --- | --- |
| Recruitment assistant | [Policy ingestion and question answering](https://github.com/KKallias/recruitment-knowledge-feedback-assistant/blob/main/workflows/01-upload-recruitment-policies-02-policy-assistant.json) | [Import and first test](https://github.com/KKallias/recruitment-knowledge-feedback-assistant#import-and-first-test). RAG foundation implemented; retrieval quality, citations, and abstention still need evaluation. |
| Sales handoff copilot | [Ingestion](https://github.com/KKallias/sales-handoff-playbook-copilot/blob/main/workflows/ingestion.json) · [Retrieval and handoff](https://github.com/KKallias/sales-handoff-playbook-copilot/blob/main/workflows/retrieval.json) | [Run the prototype](https://github.com/KKallias/sales-handoff-playbook-copilot#run-the-prototype). Prototype execution is documented; the evaluation plan covers grounding, commitments, and prompt injection. |
| Email triage assistant | [Email triage and response](https://github.com/KKallias/ai-email-triage-n8n/blob/main/workflow/ai_email_triage_response.json) | [Setup](https://github.com/KKallias/ai-email-triage-n8n#setup) · [Testing](https://github.com/KKallias/ai-email-triage-n8n#testing). Published export passed static checks; live validation remains a setup step. |

## Learning approach

I learn by building real portfolio projects and documenting the process clearly:

**learn → build → test → document → improve**

I am currently developing stronger skills in retrieval quality, grounded AI responses, workflow reliability, error handling, evaluation, and production-ready automation design.

## Connect

[LinkedIn](https://www.linkedin.com/in/konstantinoskallias/) · [GitHub](https://github.com/KKallias)
