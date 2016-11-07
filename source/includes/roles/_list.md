## List roles

```http
GET https://api.teamtailor.com/v1/locations HTTP/1.1
Authorization: Token token=abc123abc123
```

```shell
curl -X "GET" "https://api.teamtailor.com/v1/locations" \
     -H "Authorization: Token token=abc123abc123"
```

> Example response

```json
{
  "data": [
    {
      "id": "667",
      "type": "locations",
      "links": {
        "self": "http://api.teamtailor.dev/v1/locations/667"
      },
      "attributes": {
        "address": "Tegnérgatan 34",
        "city": "Stockholm",
        "country": "Sweden",
        "email": "support@teamtailor.com",
        "headquarters": true,
        "lat": "59.33855810000001",
        "long": "18.0557594",
        "name": "",
        "phone": "",
        "zip": "113 59"
      }
    },
    {
      "id": "2980",
      "type": "locations",
      "links": {
        "self": "http://api.teamtailor.dev/v1/locations/2980"
      },
      "attributes": {
        "address": "",
        "city": "Göteborg",
        "country": "Sweden",
        "email": "",
        "headquarters": false,
        "lat": "57.70887",
        "long": "11.97456",
        "name": "",
        "phone": "",
        "zip": ""
      }
    },
    {
      "id": "2981",
      "type": "locations",
      "links": {
        "self": "http://api.teamtailor.dev/v1/locations/2981"
      },
      "attributes": {
        "address": "",
        "city": "Münich",
        "country": "Germany",
        "email": "",
        "headquarters": false,
        "lat": "48.1351253",
        "long": "11.5819806",
        "name": "",
        "phone": "",
        "zip": ""
      }
    }
  ],
  "meta": {
    "record-count": 3,
    "page-count": 1
  },
  "links": {
    "first": "http://api.teamtailor.dev/v1/locations?page%5Bnumber%5D=1&page%5Bsize%5D=10",
    "last": "http://api.teamtailor.dev/v1/locations?page%5Bnumber%5D=1&page%5Bsize%5D=10"
  }
}
```
