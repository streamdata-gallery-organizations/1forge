---
swagger: "2.0"
x-collection-name: 1Forge
x-complete: 1
info:
  title: 1Forge
  description: 1forge-provides-realtime-quote-data-bid--ask-for-240-pairs--to-see-a-full-list-of-supported-currency-pairs-please-see-the-full-currency-pair-list--at-this-time-we-do-not-offer-historical-data-however-clients-are-more-than-welcome-to-archive-our-quotes-locally-for-internal-use-
  version: 1.0.0
host: forex.1forge.com
basePath: 1.0.3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /quotes:
    get:
      summary: Get Currency Quotes API
      description: Get quotes for specific currency pair(s).
      operationId: getQuotes
      x-api-path-slug: quotes-get
      parameters:
      - in: query
        name: api_key
        description: The api key
        type: string
        format: string
      - in: query
        name: format
        description: The format to return
        type: string
        format: string
      - in: query
        name: pairs
        description: A currency pair
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Quotes
  /symbols:
    get:
      summary: Get Currency Symbols API
      description: Get a list of currency symbols to use when making calls to the
        other APIs.
      operationId: getSymbols
      x-api-path-slug: symbols-get
      parameters:
      - in: query
        name: api_key
        description: The api key
        type: string
        format: string
      - in: query
        name: format
        description: The format to return
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Symbols
  /convert:
    get:
      summary: Currency Conversion API
      description: Converts between to types of currency and returns the current results.
      operationId: convertCurrency
      x-api-path-slug: convert-get
      parameters:
      - in: query
        name: api_key
        description: The api key
        type: string
        format: string
      - in: query
        name: format
        description: The format to return
        type: string
        format: string
      - in: query
        name: from
        description: Currency to convert from
        type: string
        format: string
      - in: query
        name: quantity
        description: The amount to convert
        type: string
        format: string
      - in: query
        name: to
        description: Currency to convert to
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Currency
      - Conversion
  /market_status:
    get:
      summary: Financial Market Status API
      description: Checks to see if a financial market is open or not.
      operationId: marketStatus
      x-api-path-slug: market-status-get
      parameters:
      - in: query
        name: api_key
        description: The api key
        type: string
        format: string
      - in: query
        name: format
        description: The format to return
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Markets
      - Status
  /quota:
    get:
      summary: API Usage Quota API
      description: Returns the current quota for the API consumer.
      operationId: getQuota
      x-api-path-slug: quota-get
      parameters:
      - in: query
        name: api_key
        description: The api key
        type: string
        format: string
      - in: query
        name: format
        description: The format to return
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Management
      - Quota
      - Usage
---