# Shopper Approved

Shopper Approved is an e-commerce ratings and reviews platform that helps merchants collect, manage, and display verified customer reviews to improve conversion rates and build trust. The platform powers Google Seller Ratings, enabling reviews to appear in Google Shopping ads and organic search results. Shopper Approved offers a REST API for programmatic access to review data, order submission for review collection, product review management, and site statistics.

**Human URL:** [https://www.shopperapproved.com/](https://www.shopperapproved.com/)

## APIs

### Shopper Approved API
- **Documentation:** https://help.shopperapproved.com/en/articles/9796973-how-to-use-our-api
- **Help Center:** https://help.shopperapproved.com/en/collections/10456439-api
- **Base URL:** `https://api.shopperapproved.com`
- **Authentication:** Site ID (path) + API Token (query parameter)

## Artifacts

### OpenAPI Specifications
- [shopper-approved-openapi.yml](openapi/shopper-approved-openapi.yml)

### JSON Schemas
- [shopper-approved-review-schema.json](json-schema/shopper-approved-review-schema.json)
- [shopper-approved-product-review-schema.json](json-schema/shopper-approved-product-review-schema.json)

### JSON Structure
- [shopper-approved-review-structure.json](json-structure/shopper-approved-review-structure.json)

### JSON-LD Context
- [shopper-approved-context.jsonld](json-ld/shopper-approved-context.jsonld)

### Examples
- [shopper-approved-list-reviews-example.json](examples/shopper-approved-list-reviews-example.json)
- [shopper-approved-submit-order-example.json](examples/shopper-approved-submit-order-example.json)

### Rules
- [shopper-approved-rules.yml](rules/shopper-approved-rules.yml)

### Capabilities
- [review-management.yaml](capabilities/review-management.yaml) — Reviews, product reviews, stats, order submission, and follow-up management

### Vocabulary
- [shopper-approved-vocabulary.yml](vocabulary/shopper-approved-vocabulary.yml)

## Maintainers

**Kin Lane** - kin@apievangelist.com
