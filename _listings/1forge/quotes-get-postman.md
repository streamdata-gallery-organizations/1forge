{
  "info": {
    "name": "1Forge Get Currency Quotes API",
    "_postman_id": "a3e9bf4e-c3d1-470a-89ff-4d39728c12f3",
    "description": "Get quotes for specific currency pair(s).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Quotes",
      "item": [
        {
          "id": "196ca3c6-fd47-4f56-bc20-86d84cf00122",
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
              "id": "91c6109e-2505-4d55-be63-c1615e93d4fd"
            }
          ]
        }
      ]
    }
  ]
}