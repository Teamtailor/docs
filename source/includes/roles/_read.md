## Show a Role

```http
GET https://api.teamtailor.com/v1/roles/8 HTTP/1.1
Authorization: Token token=abc123abc123
```

```shell
curl -X "GET" "https://api.teamtailor.com/v1/roles/8" \
     -H "Authorization: Token token=abc123abc123"
```

> Example response

```json
{
  "data": {
    "id": "8",
    "type": "roles",
    "links": {
      "self": "http://api.teamtailor.dev/v1/roles/8"
    },
    "attributes": {
      "name": "Designer"
    },
    "relationships": {
      "department": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/roles/8/relationships/department",
          "related": "http://api.teamtailor.dev/v1/roles/8/department"
        }
      }
    }
  }
}
```