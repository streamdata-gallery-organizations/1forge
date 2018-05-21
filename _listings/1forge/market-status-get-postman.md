{
  "info": {
    "name": "1Forge Financial Market Status API",
    "_postman_id": "5adb4fb8-905a-486f-874d-92094749ea35",
    "description": "Checks to see if a financial market is open or not.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Markets",
      "item": [
        {
          "id": "071a9472-560f-4ff1-85e2-302b6941b4af",
          "name": "marketStatus",
          "request": {
            "url": "http://forex.1forge.com/1.0.3/market_status?api_key=api_key&format=format",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Checks to see if a financial market is open or not."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59cb9252-586d-4d7b-8672-82420671ff92"
            }
          ]
        }
      ]
    }
  ]
}