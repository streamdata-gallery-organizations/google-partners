{
  "info": {
    "name": "Google Partners",
    "_postman_id": "7a30f621-176a-464c-b58c-462104ea082f",
    "description": "Searches certified companies and creates contact leads with them, and also audits the usage of clients.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "analytics",
      "item": [
        {
          "id": "863123ab-dfd8-4d2c-a141-9ad7afb0a3a7",
          "name": "partners.analytics.list",
          "request": {
            "url": "http://partners.googleapis.com/v2/analytics?pageSize=%7B%7D&pageToken=%7B%7D&requestMetadata.experimentIds=%7B%7D&requestMetadata.locale=%7B%7D&requestMetadata.partnersSessionId=%7B%7D&requestMetadata.trafficSource.trafficSourceId=%7B%7D&requestMetadata.trafficSource.trafficSubId=%7B%7D&requestMetadata.userOverrides.ipAddress=%7B%7D&requestMetadata.userOverrides.userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists analytics data for a user's associated company"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9d6d2a3-61a5-4210-9874-79ba33cb8a38"
            }
          ]
        }
      ]
    }
  ]
}