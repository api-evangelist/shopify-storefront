# Shopify Storefront API

The Shopify Storefront API is a GraphQL API that enables developers to build custom headless storefronts, purchasing flows, and commerce experiences using Shopify as a backend. The API provides programmatic access to products, collections, carts, checkout, customer accounts, and contextual pricing. It is designed for headless commerce architectures and powers the Shopify Hydrogen framework.

**Human URL:** [https://shopify.dev/docs/api/storefront](https://shopify.dev/docs/api/storefront)

## APIs

### Shopify Storefront API
- **Documentation:** https://shopify.dev/docs/api/storefront
- **Reference:** https://shopify.dev/docs/api/storefront/latest
- **Authentication:** Storefront Access Token (X-Shopify-Storefront-Access-Token header)
- **Base URL:** `https://{store_name}.myshopify.com/api/2024-10/graphql.json`
- **Getting Started:** https://shopify.dev/docs/storefronts/headless/building-with-the-storefront-api/getting-started

### Shopify Hydrogen
- **Documentation:** https://shopify.dev/docs/storefronts/headless/hydrogen
- **GitHub:** https://github.com/Shopify/hydrogen

### Shopify Buy SDK
- **Documentation:** https://shopify.github.io/js-buy-sdk/
- **GitHub:** https://github.com/Shopify/js-buy-sdk

## Artifacts

### OpenAPI Specifications
- [shopify-storefront-openapi.yml](openapi/shopify-storefront-openapi.yml)

### JSON Schemas
- [shopify-storefront-product-schema.json](json-schema/shopify-storefront-product-schema.json)
- [shopify-storefront-cart-schema.json](json-schema/shopify-storefront-cart-schema.json)

### JSON Structure
- [shopify-storefront-cart-structure.json](json-structure/shopify-storefront-cart-structure.json)

### JSON-LD Context
- [shopify-storefront-context.jsonld](json-ld/shopify-storefront-context.jsonld)

### Examples
- [shopify-storefront-query-products-example.json](examples/shopify-storefront-query-products-example.json)
- [shopify-storefront-create-cart-example.json](examples/shopify-storefront-create-cart-example.json)

### Rules
- [shopify-storefront-rules.yml](rules/shopify-storefront-rules.yml)

### Capabilities
- [headless-commerce.yaml](capabilities/headless-commerce.yaml) — Products, collections, search, cart, and customer operations

### Vocabulary
- [shopify-storefront-vocabulary.yml](vocabulary/shopify-storefront-vocabulary.yml)

## Maintainers

**Kin Lane** - kin@apievangelist.com
