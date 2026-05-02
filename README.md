# Lucidworks (lucidworks)

Lucidworks builds AI-powered search, discovery, and agent platforms used by enterprise commerce, support, and workplace teams. The Lucidworks AI Platform, Fusion, Neural Hybrid Search, Agent Studio, Commerce Studio, and Analytics Studio expose REST APIs for prediction, embedding, classification, signals capture, query rewriting, custom rule management, content chunking, and model deployment.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/lucidworks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Search, Artificial Intelligence, Enterprise Search, Vector Search, RAG, Commerce

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-04-28

## APIs

### Lucidworks AI Platform API

The Lucidworks AI Platform API exposes prediction endpoints for FAQ enrichment, keyword extraction, named entity recognition, retrieval augmented generation (RAG), summarization, passthrough LLM calls, and query rewriting.

**Human URL:** [https://doc.lucidworks.com/api-reference](https://doc.lucidworks.com/api-reference)

#### Tags

- Artificial Intelligence, Predictions, RAG, Summarization, NER, LLM

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference)
- [Authentication](https://doc.lucidworks.com/api-reference/request-access-token/request-access-token)
- [OpenAPI](openapi/lucidworks-ai-platform-openapi.yml)

### Lucidworks Embeddings and Classification API

Generates 768-dimensional vector encodings, ranked classification labels, custom model predictions, and tokenization for vector search and ML pipelines.

**Human URL:** [https://doc.lucidworks.com/api-reference](https://doc.lucidworks.com/api-reference)

#### Tags

- Embeddings, Vector Search, Classification, Tokenization, Machine Learning

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/get-predictions/english-language-model-text-encoder)
- [OpenAPI](openapi/lucidworks-embeddings-openapi.yml)

### Lucidworks Signals API

Captures and retrieves user behavior signals for click, query, cart-add, and purchase-complete events powering relevance, recommendations, and analytics.

**Human URL:** [https://doc.lucidworks.com/api-reference](https://doc.lucidworks.com/api-reference)

#### Tags

- Signals, Analytics, Click Tracking, Commerce

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/get-signals/click-signals)
- [OpenAPI](openapi/lucidworks-signals-openapi.yml)

### Lucidworks Rules and Query Rewrites API

Create, read, update, and delete custom business rules and query rewrites that drive boost, bury, pin, redirect, and synonym behaviors in search.

**Human URL:** [https://doc.lucidworks.com/api-reference/rule-management/list-rules](https://doc.lucidworks.com/api-reference/rule-management/list-rules)

#### Tags

- Business Rules, Query Rewrites, Search Tuning, Commerce

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/rule-management/list-rules)
- [Documentation](https://doc.lucidworks.com/api-reference/query-rewrite-management/list-query-rewrites)
- [OpenAPI](openapi/lucidworks-rules-openapi.yml)

### Lucidworks Content Chunking API

Splits long-form content into retrieval-ready passages using dynamic-sentence chunkers, semantic chunkers, and regex splitters for vector indexing and RAG pipelines.

**Human URL:** [https://doc.lucidworks.com/api-reference/split-content-into-chunks/chunk-text-using-the-specified-chunker](https://doc.lucidworks.com/api-reference/split-content-into-chunks/chunk-text-using-the-specified-chunker)

#### Tags

- Chunking, Content Processing, RAG, Indexing

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/split-content-into-chunks/chunk-text-using-the-specified-chunker)
- [OpenAPI](openapi/lucidworks-chunking-openapi.yml)

### Lucidworks Model Management API

Create, get, list, deploy, and delete custom models used by Lucidworks AI alongside the default model catalog for inference at query and indexing time.

**Human URL:** [https://doc.lucidworks.com/api-reference/manage-models/list-all-models](https://doc.lucidworks.com/api-reference/manage-models/list-all-models)

#### Tags

- Model Management, MLOps, Deployment

#### Properties

- [Documentation](https://doc.lucidworks.com/api-reference/manage-models/list-all-models)
- [OpenAPI](openapi/lucidworks-models-openapi.yml)

### Lucidworks Fusion REST API

Fusion REST APIs administer collections, indexing pipelines, query pipelines, connectors, and search apps inside the Lucidworks Fusion platform, including the legacy Fusion 5.7 Custom Rules API.

**Human URL:** [https://doc.lucidworks.com/docs/5/fusion/dev-portal/rest-apis](https://doc.lucidworks.com/docs/5/fusion/dev-portal/rest-apis)

#### Tags

- Fusion, Enterprise Search, Indexing, Pipelines, Connectors

#### Properties

- [Documentation](https://doc.lucidworks.com/docs/5/fusion/dev-portal/rest-apis)
- [Documentation](https://legacydoc.lucidworks.com/fusion/5.7/331/custom-rules-api)

## Common Properties

- [Website](https://lucidworks.com)
- [Documentation](https://doc.lucidworks.com)
- [APIReference](https://doc.lucidworks.com/api-reference)
- [Authentication](https://doc.lucidworks.com/api-reference/request-access-token/request-access-token)
- [SDK](https://doc.lucidworks.com/docs/5/fusion/dev-portal/connectors-sdk/overview)
- [Blog](https://lucidworks.com/blog)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
