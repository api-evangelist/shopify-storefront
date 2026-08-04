# Shopify Storefront API (shopify-storefront)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The Shopify Storefront API is a GraphQL API that enables developers to build custom headless storefronts, purchasing flows, and commerce experiences using Shopify as a backend. The API provides programmatic access to products, collections, carts, checkout, customer accounts, and contextual pricing. It is designed for headless commerce architectures and powers the Shopify Hydrogen framework.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/shopify-storefront/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shopify-storefront/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Commerce
- Ecommerce
- Headless
- GraphQL
- Storefront
- Products
- Cart
- Checkout

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Shopify Storefront API

The Shopify Storefront API is a GraphQL API for building headless commerce experiences. It provides access to products, collections, cart, checkout, customer accounts, and contextual pricing. All requests use GraphQL over HTTPS and require a Storefront API access token. The Storefront API supports both unauthenticated (public) and customer-authenticated access patterns.

- **Human URL:** [https://shopify.dev/docs/api/storefront](https://shopify.dev/docs/api/storefront)
- **Base URL:** `https://{store_name}.myshopify.com/api/2024-10/graphql.json`

#### Tags

- Commerce
- Ecommerce
- Headless
- GraphQL
- Products
- Cart
- Checkout

#### Properties

- [Documentation](https://shopify.dev/docs/api/storefront)
- [Reference](https://shopify.dev/docs/api/storefront/latest)
- [Getting Started](https://shopify.dev/docs/storefronts/headless/building-with-the-storefront-api/getting-started)
- [Authentication](https://shopify.dev/docs/storefronts/headless/building-with-the-storefront-api/get-started-with-the-storefront-api)
- [Rate Limits](https://shopify.dev/docs/api/usage/rate-limits)
- [Versioning](https://shopify.dev/docs/api/usage/versioning)
- [OpenAPI](openapi/shopify-storefront-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shopify-storefront.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shopify-storefront.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/shopify-storefront-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/shopify-storefront-cart-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/shopify-storefront-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/shopify-storefront-rules.yml)
- [Vocabulary](vocabulary/shopify-storefront-vocabulary.yml)

### Shopify Hydrogen

Hydrogen is Shopify's opinionated React-based framework for building headless storefronts powered by the Storefront API. Hydrogen provides components, hooks, and utilities optimized for commerce including streaming SSR, React Server Components, and built-in Shopify data fetching.

- **Human URL:** [https://shopify.dev/docs/storefronts/headless/hydrogen](https://shopify.dev/docs/storefronts/headless/hydrogen)

#### Tags

- Commerce
- Headless
- React
- Framework
- SSR

#### Properties

- [Documentation](https://shopify.dev/docs/storefronts/headless/hydrogen)
- [Getting Started](https://shopify.dev/docs/storefronts/headless/hydrogen/getting-started)
- [SDK](https://github.com/Shopify/hydrogen)
- [Postman Collection](collections/shopify-storefront.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shopify-storefront.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Shopify Buy SDK

The Shopify JavaScript Buy SDK is a lightweight library that enables developers to integrate Shopify's storefront capabilities into any website or application. The SDK wraps the Storefront API and provides methods for fetching products, collections, and managing carts.

- **Human URL:** [https://shopify.github.io/js-buy-sdk/](https://shopify.github.io/js-buy-sdk/)

#### Tags

- Commerce
- JavaScript
- SDK
- Cart

#### Properties

- [Documentation](https://shopify.github.io/js-buy-sdk/)
- [SDK](https://github.com/Shopify/js-buy-sdk)
- [Postman Collection](collections/shopify-storefront.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shopify-storefront.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/shopify)
- [Integrations](https://shopify.dev/docs/apps/build)
- [L L Ms Txt](https://shopify.dev/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
