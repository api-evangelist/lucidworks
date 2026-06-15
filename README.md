# Lucidworks (lucidworks)

Lucidworks builds AI-powered search, discovery, and agent platforms used by enterprise commerce, support, and workplace teams. The Lucidworks AI Platform, Fusion, Neural Hybrid Search, Agent Studio, Commerce Studio, and Analytics Studio expose REST APIs for prediction, embedding, classification, signals capture, query rewriting, custom rule management, content chunking, and model deployment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Search
- Artificial Intelligence
- Enterprise Search
- Vector Search
- RAG
- Commerce

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-05-19

## APIs

### Lucidworks AI Platform API

The Lucidworks AI Platform API exposes prediction endpoints for FAQ enrichment, keyword extraction, named entity recognition, retrieval augmented generation (RAG), summarization, passthrough LLM calls, and query rewriting. Developers can invoke pre-built use cases or chain custom predictions, then fetch results asynchronously by prediction ID.

- **Human URL:** [https://doc.lucidworks.com/api-reference](https://doc.lucidworks.com/api-reference)
- **Base URL:** `https://api.lucidworks.ai`

#### Tags

- Artificial Intelligence
- Predictions
- RAG
- Summarization
- NER
- LLM

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference)
- [Authentication](https://doc.lucidworks.com/api-reference/request-access-token/request-access-token)
- [OpenAPI](openapi/lucidworks-ai-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lucidworks-ai-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-ai-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucidworks Embeddings and Classification API

The Embeddings and Classification API generates 768-dimensional vector encodings using the English Language Model text encoder, returns ranked classification labels, exposes custom model predictions, and tokenizes inputs by model ID for use in vector search and downstream ML pipelines.

- **Human URL:** [https://doc.lucidworks.com/api-reference](https://doc.lucidworks.com/api-reference)
- **Base URL:** `https://api.lucidworks.ai`

#### Tags

- Embeddings
- Vector Search
- Classification
- Tokenization
- Machine Learning

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/get-predictions/english-language-model-text-encoder)
- [OpenAPI](openapi/lucidworks-embeddings-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lucidworks-embeddings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-embeddings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucidworks Signals API

The Signals API captures and retrieves user behavior signals for click, query, cart-add, and purchase-complete events. Signals power relevance tuning, recommendations, and analytics across Commerce Studio and the Analytics Studio.

- **Human URL:** [https://doc.lucidworks.com/api-reference](https://doc.lucidworks.com/api-reference)
- **Base URL:** `https://api.lucidworks.ai`

#### Tags

- Signals
- Analytics
- Click Tracking
- Commerce

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/get-signals/click-signals)
- [OpenAPI](openapi/lucidworks-signals-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lucidworks-signals.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-signals.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucidworks Rules and Query Rewrites API

The Rules and Query Rewrites API allows commerce and search teams to create, read, update, and delete custom business rules and query rewrites. Rules drive boost, bury, pin, redirect, and synonym behaviors that personalize search results without code changes.

- **Human URL:** [https://doc.lucidworks.com/api-reference/rule-management/list-rules](https://doc.lucidworks.com/api-reference/rule-management/list-rules)
- **Base URL:** `https://api.lucidworks.ai`

#### Tags

- Business Rules
- Query Rewrites
- Search Tuning
- Commerce

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/rule-management/list-rules)
- [Documentation](https://doc.lucidworks.com/api-reference/query-rewrite-management/list-query-rewrites)
- [OpenAPI](openapi/lucidworks-rules-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lucidworks-rules.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-rules.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucidworks Content Chunking API

The Content Chunking API splits long-form content into retrieval-ready passages using dynamic-sentence chunkers, semantic chunkers, and regex splitters. Chunked output feeds vector indexing and RAG pipelines.

- **Human URL:** [https://doc.lucidworks.com/api-reference/split-content-into-chunks/chunk-text-using-the-specified-chunker](https://doc.lucidworks.com/api-reference/split-content-into-chunks/chunk-text-using-the-specified-chunker)
- **Base URL:** `https://api.lucidworks.ai`

#### Tags

- Chunking
- Content Processing
- RAG
- Indexing

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/split-content-into-chunks/chunk-text-using-the-specified-chunker)
- [OpenAPI](openapi/lucidworks-chunking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lucidworks-chunking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-chunking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucidworks Model Management API

The Model Management API lets teams create, get, list, deploy, and delete models used by Lucidworks AI. Custom models can be registered and deployed alongside the default catalog for inference at query and indexing time.

- **Human URL:** [https://doc.lucidworks.com/api-reference/manage-models/list-all-models](https://doc.lucidworks.com/api-reference/manage-models/list-all-models)
- **Base URL:** `https://api.lucidworks.ai`

#### Tags

- Model Management
- MLOps
- Deployment

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/manage-models/list-all-models)
- [OpenAPI](openapi/lucidworks-models-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lucidworks-models.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-models.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucidworks Fusion REST API

Fusion REST APIs administer collections, indexing pipelines, query pipelines, connectors, and search apps inside the Lucidworks Fusion platform. The legacy Custom Rules API for Fusion 5.7 is part of this family of administrative endpoints.

- **Human URL:** [https://doc.lucidworks.com/docs/5/fusion/dev-portal/rest-apis](https://doc.lucidworks.com/docs/5/fusion/dev-portal/rest-apis)

#### Tags

- Fusion
- Enterprise Search
- Indexing
- Pipelines
- Connectors

#### Properties

- [Documentation](https://doc.lucidworks.com/docs/5/fusion/dev-portal/rest-apis)
- [Documentation](https://legacydoc.lucidworks.com/fusion/5.7/331/custom-rules-api)
- [Postman Collection](collections/lucidworks-ai-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-ai-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/lucidworks-chunking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-chunking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/lucidworks-embeddings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-embeddings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/lucidworks-models.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-models.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/lucidworks-rules.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-rules.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/lucidworks-signals.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidworks-signals.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/lucidworks)
- [LinkedIn](https://www.linkedin.com/company/lucidworks)
- [Website](https://lucidworks.com)
- [Documentation](https://doc.lucidworks.com)
- [API Reference](https://doc.lucidworks.com/api-reference)
- [Authentication](https://doc.lucidworks.com/api-reference/request-access-token/request-access-token)
- [SDK](https://doc.lucidworks.com/docs/5/fusion/dev-portal/connectors-sdk/overview)
- [Blog](https://lucidworks.com/blog)
- [L L Ms Txt](https://lucidworks.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
