# Claude (claude)

Anthropic's Claude AI assistant API for natural language processing and conversation.

**APIs.json:** [https://www.anthropic.com](https://www.anthropic.com)

## Tags

- Artificial Intelligence
- Chatbot
- Conversational AI
- Generative AI
- Large Language Models
- Machine Learning
- Natural Language Processing

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Claude Messages API

Primary API for sending messages to Claude and receiving responses.

- **Human URL:** [https://docs.anthropic.com/en/api/messages](https://docs.anthropic.com/en/api/messages)
- **Base URL:** `https://api.anthropic.com/v1`

#### Tags

- AI
- Conversational AI
- Large Language Models
- Natural Language Processing

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/messages)
- [OpenAPI](openapi/claude-messages-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/claude-messages-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claude-messages-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.anthropic.com/claude/reference/authentication)
- [Pricing](https://www.anthropic.com/pricing)
- [Rate Limits](https://docs.anthropic.com/en/api/rate-limits)
- [Getting Started](https://docs.anthropic.com/en/api/getting-started)
- [JSON Schema](json-schema/claude-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-create-message-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-usage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-tool-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-tool-use-block-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-content-block-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-text-block-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-thinking-block-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-token-count-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-count-tokens-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-metadata-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-output-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-thinking-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-tool-choice-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-cache-control-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-content-block-param-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-text-block-param-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-image-block-param-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-document-block-param-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-tool-use-block-param-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-tool-result-block-param-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-thinking-block-param-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-message-param-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-message-batch-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-message-batch-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-message-batch-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-create-message-batch-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-batch-request-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-deleted-message-batch-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-model-info-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-messages-model-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/claude-tool-use-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/claude-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/claude-messages-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [SDK](https://github.com/anthropics/anthropic-sdk-python)
- [SDK](https://github.com/anthropics/anthropic-sdk-typescript)

### Claude Message Batches API

API for asynchronously processing large volumes of message requests at reduced cost with 50 percent discount.

- **Human URL:** [https://docs.anthropic.com/en/api/creating-message-batches](https://docs.anthropic.com/en/api/creating-message-batches)
- **Base URL:** `https://api.anthropic.com/v1`

#### Tags

- AI
- Asynchronous
- Batch Processing
- Large Language Models

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/creating-message-batches)
- [Postman Collection](collections/claude-messages-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claude-messages-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Claude Models API

API for listing and retrieving metadata about available Claude models including capabilities and context windows.

- **Human URL:** [https://docs.anthropic.com/en/api/models-list](https://docs.anthropic.com/en/api/models-list)
- **Base URL:** `https://api.anthropic.com/v1`

#### Tags

- AI
- Large Language Models
- Models

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/models-list)
- [Models](https://docs.anthropic.com/en/docs/about-claude/models)
- [Postman Collection](collections/claude-messages-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claude-messages-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Claude Files API

API for uploading and managing files to reference in Claude API requests without re-uploading content each time.

- **Human URL:** [https://docs.anthropic.com/en/docs/build-with-claude/files](https://docs.anthropic.com/en/docs/build-with-claude/files)
- **Base URL:** `https://api.anthropic.com/v1`

#### Tags

- AI
- Document Processing
- File Management
- Files

#### Properties

- [Documentation](https://docs.anthropic.com/en/docs/build-with-claude/files)
- [Postman Collection](collections/claude-messages-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claude-messages-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Claude Admin API

API for programmatically managing organization resources including members workspaces API keys and invites.

- **Human URL:** [https://docs.anthropic.com/en/api/administration-api](https://docs.anthropic.com/en/api/administration-api)
- **Base URL:** `https://api.anthropic.com/v1`

#### Tags

- Administration
- AI
- API Keys
- Organization Management
- Workspaces

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/administration-api)
- [Postman Collection](collections/claude-messages-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claude-messages-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Claude Usage and Cost API

API for tracking token consumption and costs across your organization with breakdowns by model workspace and service tier.

- **Human URL:** [https://docs.anthropic.com/en/api/usage-cost-api](https://docs.anthropic.com/en/api/usage-cost-api)
- **Base URL:** `https://api.anthropic.com/v1`

#### Tags

- AI
- Analytics
- Cost Tracking
- Usage

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/usage-cost-api)
- [Postman Collection](collections/claude-messages-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claude-messages-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Claude Text Completions API

Legacy API for generating text completions - deprecated in favor of the Messages API.

- **Human URL:** [https://docs.anthropic.com/en/api/complete](https://docs.anthropic.com/en/api/complete)
- **Base URL:** `https://api.anthropic.com/v1`

#### Tags

- AI
- Large Language Models
- Legacy
- Text Completion

#### Properties

- [Documentation](https://docs.anthropic.com/en/api/complete)
- [Postman Collection](collections/claude-messages-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/claude-messages-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/showcase/claude)
- [Portal](https://console.anthropic.com)
- [Documentation](https://docs.anthropic.com)
- [Getting Started](https://docs.anthropic.com/en/docs/get-started)
- [Pricing](https://www.anthropic.com/pricing)
- [Rate Limits](https://docs.anthropic.com/en/api/rate-limits)
- [Authentication](https://docs.anthropic.com/en/api/getting-started)
- [Changelog](https://docs.anthropic.com/en/release-notes/api)
- [Status Page](https://status.anthropic.com)
- [Blog](https://www.anthropic.com/news)
- [Support](https://support.anthropic.com)
- [Terms of Service](https://www.anthropic.com/legal/commercial-terms)
- [Privacy Policy](https://www.anthropic.com/legal/privacy)
- [GitHub Organization](https://github.com/anthropics)
- [Spectral Rules](rules/claude-spectral-rules.yml)
- [Vocabulary](vocabulary/claude-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [M C P Server](https://github.com/anthropics/claude-ai-mcp)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
**Email:** support@anthropic.com
**URL:** https://www.anthropic.com
