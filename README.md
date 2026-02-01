![Workflow thumbnail](assets/thumbnail.svg)

![Workflow thumbnail](assets/thumbnail.svg)

![Workflow thumbnail](assets/thumbnail.svg)

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Automate Document Q&A with Multi-Agent RAG Orchestration using Contextual AI & Gemini

Advanced n8n automation for Automate Document Q&A with Multi-Agent RAG Orchestration using Contextual AI & Gemini.

## Overview
- Category: Internal Wiki, AI RAG
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Effortlessly manage multiple RAG AI agents with automated selection, real-time updates, and easy customization. Boost productivitylearn more today!

## Included Files
- `workflow.json`
- `metadata.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.chatTrigger`
- `@n8n/n8n-nodes-langchain.lmChatGoogleGemini`
- `@n8n/n8n-nodes-langchain.memoryBufferWindow`
- `n8n-nodes-base.code`
- `n8n-nodes-base.formTrigger`
- `n8n-nodes-base.if`
- `n8n-nodes-base.splitInBatches`
- `n8n-nodes-base.splitOut`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.wait`
- `n8n-nodes-contextualai.contextualAi`
- `n8n-nodes-contextualai.contextualAiTool`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.