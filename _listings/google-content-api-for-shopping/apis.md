---
name: Google Content API for Shopping
x-slug: google-content-api-for-shopping
description: 'API allowing retailers to manage their product feed content programmatically.
  Providing item-level data quality information: See if an item was disapproved because
  a landing page URL isn&rsquo;t working on a mobile device or if unique product identifiers
  are inaccurate. Faster pricing and availability updates: Ensure customers have the
  latest price-points and know what&rsquo;s in-stock before they click through to
  your site. More integration options: The newer API supports a broader choice of
  programming languages and data formats.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Batch
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/google-content-api-for-shopping/apis.md
specificationVersion: "0.14"
apis:
- name: Content API for Shopping - Account Batch
  x-api-slug: accountsbatch-post
  description: Retrieves, inserts, updates, and deletes multiple Merchant Center (sub-)accounts
    in a single request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/google-content-api-for-shopping/accountsbatch-post-openapi.md
- name: Content API for Shopping - Account Status Batch
  x-api-slug: accountstatusesbatch-post
  description: Retrieves account batch status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/google-content-api-for-shopping/accountstatusesbatch-post-openapi.md
- name: Content API for Shopping - Product Batch
  x-api-slug: productstatusesbatch-post
  description: Gets the statuses of multiple products in a single request. This method
    can only be called for non-multi-client accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/google-content-api-for-shopping/productstatusesbatch-post-openapi.md
- name: Content API for Shopping - Account Batches
  x-api-slug: accountshippingbatch-post
  description: Retrieves and updates the shipping settings of multiple accounts in
    a single request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-shopping-API1.jpg
  humanURL: https://developers.google.com/shopping-content/v2/quickstart
  baseURL: ://www.googleapis.com//content/v2
  tags: Shopping, Commerce, Content, Google APIs, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/google-content-api-for-shopping/accountshippingbatch-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.container.engine.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.content.api.for.shopping.stack.network
- type: x-best-practices
  url: https://developers.google.com/shopping-content/v2/best-practices
- type: x-code
  url: https://developers.google.com/shopping-content/v2/libraries
- type: x-testing
  url: https://developers.google.com/shopping-content/v2/how-tos/testing
- type: x-website
  url: https://developers.google.com/shopping-content/v2/quickstart
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---