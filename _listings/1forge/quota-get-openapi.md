---
swagger: "2.0"
x-collection-name: 1Forge
x-complete: 0
info:
  title: 1Forge API Usage Quota API
  description: Returns the current quota for the API consumer.
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
x-streamrank:
  polling_total_time_average: "0.59"
  polling_size_download_average: "81.06"
  streaming_total_time_average: "0.4"
  streaming_size_download_average: "40.75"
  change_yes: "2"
  change_no: "187"
  time_percentage: "32"
  size_percentage: "50"
  change_percentage: "1"
  last_run: "2018-02-19"
  days_run: "0"
  minute_run: "0"
---