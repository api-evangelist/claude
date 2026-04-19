# Claude (claude)
Anthropic's Claude AI assistant API for natural language processing and conversation.

**URL:** [Visit APIs.json URL](https://www.anthropic.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Artificial Intelligence, Chatbot, Conversational AI, Generative AI, Large Language Models, Machine Learning, Natural Language Processing

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-18

## APIs

### Claude Messages API
Primary API for sending messages to Claude and receiving responses.

**Human URL:** [https://docs.anthropic.com/en/api/messages](https://docs.anthropic.com/en/api/messages)

#### Tags:

 - AI, Conversational AI, Large Language Models, Natural Language Processing

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/messages)
- [OpenAPI](openapi/claude-messages-api.yml)
- [Authentication](https://docs.anthropic.com/claude/reference/authentication)
- [Pricing](https://www.anthropic.com/pricing)
- [RateLimits](https://docs.anthropic.com/en/api/rate-limits)
- [GettingStarted](https://docs.anthropic.com/en/api/getting-started)
- [Python SDK](https://github.com/anthropics/anthropic-sdk-python)
- [TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript)

### Claude Message Batches API
API for asynchronously processing large volumes of message requests at reduced cost with 50 percent discount.

**Human URL:** [https://docs.anthropic.com/en/api/creating-message-batches](https://docs.anthropic.com/en/api/creating-message-batches)

#### Tags:

 - AI, Asynchronous, Batch Processing, Large Language Models

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/creating-message-batches)

### Claude Models API
API for listing and retrieving metadata about available Claude models including capabilities and context windows.

**Human URL:** [https://docs.anthropic.com/en/api/models-list](https://docs.anthropic.com/en/api/models-list)

#### Tags:

 - AI, Large Language Models, Models

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/models-list)
- [Models](https://docs.anthropic.com/en/docs/about-claude/models)

### Claude Files API
API for uploading and managing files to reference in Claude API requests without re-uploading content each time.

**Human URL:** [https://docs.anthropic.com/en/docs/build-with-claude/files](https://docs.anthropic.com/en/docs/build-with-claude/files)

#### Tags:

 - AI, Document Processing, File Management, Files

#### Properties

- [Documentation](https://docs.anthropic.com/en/docs/build-with-claude/files)

### Claude Admin API
API for programmatically managing organization resources including members workspaces API keys and invites.

**Human URL:** [https://docs.anthropic.com/en/api/administration-api](https://docs.anthropic.com/en/api/administration-api)

#### Tags:

 - Administration, AI, API Keys, Organization Management, Workspaces

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/administration-api)

### Claude Usage and Cost API
API for tracking token consumption and costs across your organization with breakdowns by model workspace and service tier.

**Human URL:** [https://docs.anthropic.com/en/api/usage-cost-api](https://docs.anthropic.com/en/api/usage-cost-api)

#### Tags:

 - AI, Analytics, Cost Tracking, Usage

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/usage-cost-api)

### Claude Text Completions API
Legacy API for generating text completions - deprecated in favor of the Messages API.

**Human URL:** [https://docs.anthropic.com/en/api/complete](https://docs.anthropic.com/en/api/complete)

#### Tags:

 - AI, Large Language Models, Legacy, Text Completion

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/complete)

## Common Properties

- [Portal](https://console.anthropic.com)
- [Documentation](https://docs.anthropic.com)
- [GettingStarted](https://docs.anthropic.com/en/docs/get-started)
- [Pricing](https://www.anthropic.com/pricing)
- [RateLimits](https://docs.anthropic.com/en/api/rate-limits)
- [Authentication](https://docs.anthropic.com/en/api/getting-started)
- [ChangeLog](https://docs.anthropic.com/en/release-notes/api)
- [StatusPage](https://status.anthropic.com)
- [Blog](https://www.anthropic.com/news)
- [Support](https://support.anthropic.com)
- [TermsOfService](https://www.anthropic.com/legal/commercial-terms)
- [PrivacyPolicy](https://www.anthropic.com/legal/privacy)
- [GitHubOrganization](https://github.com/anthropics)

## Features

| Name | Description |
|------|-------------|
| Multi-Turn Conversations | Maintain context across multiple message exchanges for natural dialogue interactions. |
| Tool Use | Enable Claude to call external tools and functions to perform actions and retrieve data. |
| Vision | Process and analyze images alongside text for multimodal understanding. |
| Extended Thinking | Allow Claude to reason step-by-step for complex tasks with visible thinking process. |
| Streaming Responses | Receive responses in real-time via server-sent events for responsive user experiences. |
| Message Batches | Process large volumes of requests asynchronously at 50 percent reduced cost. |
| Token Counting | Pre-calculate token usage for messages including tools, images, and documents. |

## Use Cases

| Name | Description |
|------|-------------|
| AI-Powered Chat Applications | Build conversational interfaces with context-aware responses and tool integration. |
| Content Generation | Generate, edit, and transform text content for marketing, documentation, and creative writing. |
| Code Assistance | Use Claude for code generation, review, debugging, and technical documentation. |
| Document Analysis | Extract information, summarize, and answer questions about documents and images. |
| Batch Processing | Process large datasets of prompts efficiently using the Message Batches API. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon Bedrock | Access Claude models through AWS Bedrock for enterprise deployment with AWS infrastructure. |
| Google Cloud Vertex AI | Use Claude on Google Cloud through Vertex AI integration. |
| LangChain | Integrate Claude into LangChain pipelines for advanced AI application development. |
| MCP Protocol | Connect Claude to external data sources and tools via the Model Context Protocol. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Claude Messages API OpenAPI](openapi/claude-messages-api.yml)

### JSON Schema

- [Message Schema](json-schema/claude-message-schema.json)
- [Create Message Request Schema](json-schema/claude-messages-create-message-request-schema.json)
- [Tool Use Schema](json-schema/claude-tool-use-schema.json)
- [Error Schema](json-schema/claude-messages-error-schema.json)

### JSON-LD

- [Claude Context](json-ld/claude-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Claude Messages API](capabilities/shared/claude-messages.yaml) — 10 operations for message creation, batches, and model discovery

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [AI Messaging](capabilities/ai-messaging.yaml) | Claude Messages API | 10 | AI Application Developer |

## Vocabulary

- [Claude Vocabulary](vocabulary/claude-vocabulary.yaml)

## Rules

- [Claude Spectral Rules](rules/claude-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
