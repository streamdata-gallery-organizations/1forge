{
  "info": {
    "name": "1Forge Currency Conversion API",
    "_postman_id": "1214d7e0-30f2-4c09-b71d-8805a6676ea1",
    "description": "Converts between to types of currency and returns the current results.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Quotes",
      "item": [
        {
          "id": "f2c5c617-40f8-47bf-b854-0680e4ebfa9f",
          "name": "getQuotes",
          "request": {
            "url": "http://forex.1forge.com/1.0.3/quotes?api_key=api_key&format=format&pairs=pairs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get quotes for specific currency pair(s)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fef8ee98-2d9c-4fbf-a1cf-9c9546c860ff"
            }
          ]
        }
      ]
    },
    {
      "name": "Symbols",
      "item": [
        {
          "id": "8b855d0d-7638-415b-a72f-cee6efd864a8",
          "name": "getSymbols",
          "request": {
            "url": "http://forex.1forge.com/1.0.3/symbols?api_key=api_key&format=format",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of currency symbols to use when making calls to the other APIs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9070b41e-8c64-4a55-b909-7d71886bec03"
            }
          ]
        }
      ]
    },
    {
      "name": "Currency",
      "item": [
        {
          "id": "295cd827-6149-4e43-b06f-52c87a8e6f2c",
          "name": "convertCurrency",
          "request": {
            "url": "http://forex.1forge.com/1.0.3/convert?api_key=api_key&format=format&from=from&quantity=quantity&to=to",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Converts between to types of currency and returns the current results."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15c37d0d-e0cc-42be-ae96-a7044572378b"
            }
          ]
        }
      ]
    }
  ]
}