---
name: Getty Images
x-slug: getty-images
description: Find high resolution royalty-free images, editorial stock photos, vector
  art, video footage clips and stock music licensing at the richest image search photo
  library online.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1013-getty-images.jpg
x-kinRank: "8"
x-alexaRank: "1939"
tags: Batch
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/getty-images/apis.md
specificationVersion: "0.14"
apis:
- name: Getty Images Reports Usage Batches
  x-api-slug: getty-images
  description: "# Report Usage\r\n\r\nUse this endpoint to report the usages of a
    set of assets. The count of assets submitted in a single batch to this endpoint
    is limited to 1000. Note that all asset Ids specified must be valid or the operation
    will fail causing no usages to be recorded. In this case, you will need to remove
    the invalid asset Ids from the query request and re-submit the query.\r\n\r\n##
    \ Quickstart\r\n\r\nYou'll need an API key and a [Resource Owner Grant](http://developers.gettyimages.com/en/authorization-faq.html)
    access token to use this resource.\r\nPlease see our [Getting Started](http://developers.gettyimages.com/en/getting-started.html)
    page for more information on how to sign up for an API key. \r\n\r\n\r\n_Note_:
    Date of use can be in any unambiguous date format."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1013-getty-images.jpg
  humanURL: http://www.gettyimages.com/
  baseURL: https://api.gettyimages.com////v3/usage-batches/{id}
  tags: Images,Batches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/getty-images/v3usagebatchesid-put-openapi.md
- name: Getty Images
  x-api-slug: getty-images
  description: Find high resolution royalty-free images, editorial stock photos, vector
    art, video footage clips and stock music licensing at the richest image search
    photo library online.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1013-getty-images.jpg
  humanURL: http://www.gettyimages.com/
  baseURL: https://api.gettyimages.com//
  tags: Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/batch/master/_listings/getty-images/openapi.md
x-common:
- type: x-authentication
  url: https://github.com/gettyimages/connect#authentication
- type: x-base
  url: https://connect.gettyimages.com/
- type: x--net-sdk
  url: https://github.com/gettyimages/connect_sdk_csharp
- type: x-crunchbase
  url: https://crunchbase.com/organization/gettyimages
- type: x-crunchbase
  url: http://www.crunchbase.com/company/ge-tt
- type: x-developer
  url: http://api.gettyimages.com/
- type: x-documentation
  url: https://api.gettyimages.com/swagger/ui/index.html
- type: x-email
  url: privacy@gettyimages.com
- type: x-email
  url: sales@gettyimages.com
- type: x-email
  url: copyright@gettyimages.com
- type: x-embeddable
  url: https://github.com/gettyimages/connect#oembed
- type: x-forum
  url: http://api.gettyimages.com/forum
- type: x-getting-started
  url: https://github.com/gettyimages/connect#getting-started
- type: x-github
  url: https://github.com/gettyimages
- type: x-java-sdk
  url: https://github.com/gettyimages/connect_sdk_java
- type: x-node-js-sdk
  url: https://github.com/gettyimages/connect_sdk_nodejs
- type: x-objectivec-sdk
  url: https://github.com/gettyimages/connect_sdk_objective-c
- type: x-php-sdk
  url: https://github.com/gettyimages/connect_sdk_php
- type: x-pricing
  url: http://www.gettyimages.com/subscribe
- type: x-ruby-sdk
  url: https://github.com/gettyimages/connect_sdk_ruby
- type: x-twitter
  url: https://twitter.com/GettyImages
- type: x-website
  url: http://www.gettyimages.com/
- type: x-website
  url: http://gettyimages.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---