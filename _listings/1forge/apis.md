---
name: 1Forge
x-slug: 1forge
description: Exchange Rate API, Currency Conversion API and Realtime Forex Quote API.
  Serving realtime tick data for over 500 forex currency pairs and commodities.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/1forge-logo.png
x-kinRank: "8"
x-alexaRank: "648546"
tags: 1Forge
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/apis.md
specificationVersion: "0.14"
apis:
- name: 1Forge Get Currency Quotes API
  x-api-slug: 1forge
  description: Get quotes for specific currency pair(s).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/1forge-logo.png
  humanURL: http://1forge.com
  baseURL: https://forex.1forge.com/1.0.3///quotes
  tags: Quotes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/quotes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/quotes-get-openapi.md
- name: 1Forge Get Currency Symbols API
  x-api-slug: 1forge
  description: Get a list of currency symbols to use when making calls to the other
    APIs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/1forge-logo.png
  humanURL: http://1forge.com
  baseURL: https://forex.1forge.com/1.0.3///symbols
  tags: Symbols
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/symbols-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/symbols-get-openapi.md
- name: 1Forge Currency Conversion API
  x-api-slug: 1forge
  description: Converts between to types of currency and returns the current results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/1forge-logo.png
  humanURL: http://1forge.com
  baseURL: https://forex.1forge.com/1.0.3///convert
  tags: Currency, Conversion
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/convert-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/convert-get-openapi.md
- name: 1Forge Financial Market Status API
  x-api-slug: 1forge
  description: Checks to see if a financial market is open or not.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/1forge-logo.png
  humanURL: http://1forge.com
  baseURL: https://forex.1forge.com/1.0.3///market_status
  tags: Markets, Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/market-status-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/market-status-get-openapi.md
- name: 1Forge API Usage Quota API
  x-api-slug: 1forge
  description: Returns the current quota for the API consumer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/1forge-logo.png
  humanURL: http://1forge.com
  baseURL: https://forex.1forge.com/1.0.3///quota
  tags: Management, Quota, Usage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/quota-get-openapi.md
- name: 1Forge
  x-api-slug: 1forge
  description: Exchange Rate API, Currency Conversion API and Realtime Forex Quote
    API. Serving realtime tick data for over 500 forex currency pairs and commodities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/1forge-logo.png
  humanURL: http://1forge.com
  baseURL: https://forex.1forge.com/1.0.3/
  tags: 1Forge
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/1forge/master/_listings/1forge/openapi.md
x-common:
- type: x-code
  url: https://1forge.com/forex-data-api/libraries
- type: x-documentation
  url: https://1forge.com/forex-data-api/api-documentation
- type: x-email
  url: contact@1forge.com
- type: x-embeddable
  url: https://1forge.com/forex-data-api/widgets
- type: x-faq
  url: https://1forge.com/forex-data-api/faq
- type: x-github
  url: https://github.com/1Forge
- type: x-license-agreement
  url: https://1forge.com/forex-data-api/license-agreement
- type: x-pricing
  url: https://1forge.com/forex-data-api/pricing
- type: x-privacy-policy
  url: https://1forge.com/privacy-policy
- type: x-selfservice-registration
  url: https://1forge.com/register
- type: x-terms-of-service
  url: https://1forge.com/forex-data-api/terms-of-use
- type: x-website
  url: http://1forge.com
- type: x-website
  url: https://1forge.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---