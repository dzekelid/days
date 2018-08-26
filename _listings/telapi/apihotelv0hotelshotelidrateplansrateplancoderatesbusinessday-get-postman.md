{
  "info": {
    "name": "hetras Hotel API Version 0 Get the setup of a daily rate for a specific business day and rateplan.",
    "_postman_id": "b4619943-e63e-4654-bbba-af3b874dcdd7",
    "description": "Read the setup of the daily rate for the defined rateplan for that specific business day.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Setup",
      "item": [
        {
          "id": "36a9cfe3-f2eb-40ce-a9a1-5d67e894c7dd",
          "name": "RatePlans_GetRate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.hetras-certification.net",
              "path": [
                "api/hotel/v0/hotels/:hotelId/rateplans/:rateplanCode/rates/:businessDay"
              ],
              "variable": [
                {
                  "id": "businessDay",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "hotelId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "rateplanCode",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "App-Id",
                "value": "{}",
                "description": "Application identifier",
                "disabled": false
              },
              {
                "key": "App-Key",
                "value": "{}",
                "description": "Application key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Read the setup of the daily rate for the defined rateplan for that specific business day."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca8e4af5-b908-4e8f-9802-973a594e2aa5"
            }
          ]
        }
      ]
    }
  ]
}