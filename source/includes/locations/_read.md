## Show a Location

```http
GET https://api.teamtailor.com/v1/locations/667 HTTP/1.1
Authorization: Token token=abc123abc123
```

```shell
curl -X "GET" "https://api.teamtailor.com/v1/locations/667" \
     -H "Authorization: Token token=abc123abc123"
```

> Example response

```json
{
  "data": {
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
  }
}
```