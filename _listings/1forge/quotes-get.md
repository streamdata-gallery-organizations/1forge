---
swagger: "2.0"
info:
  title: 1Forge
  description: 1Forge provides real-time quote data (bid &amp; ask) for 240+ pairs.
    To see a full list of supported currency pairs, please see the full currency pair
    list. At this time, we do not offer historical data, however, clients are more
    than welcome to archive our quotes locally for internal use.
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
      description: Get quotes for specific currency pair(s)
      operationId: getQuotes
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
      - quotes
definitions: []
x-collection-name: 1Forge
x-streamrank:
  polling_total_time_average: "0.79"
  polling_size_download_average: "9410.7"
  streaming_total_time_average: "0.57"
  streaming_size_download_average: "4708.32"
  change_yes: "539"
  change_no: "3202"
  time_percentage: "28"
  size_percentage: "50"
  change_percentage: "14"
  last_run: "2018-02-19"
  days_run: "3"
  minute_run: "0"
---