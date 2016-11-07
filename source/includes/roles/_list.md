## List roles

```http
GET https://api.teamtailor.com/v1/roles HTTP/1.1
Authorization: Token token=abc123abc123
```

```shell
curl -X "GET" "https://api.teamtailor.com/v1/roles" \
     -H "Authorization: Token token=abc123abc123"
```

> Example response

```json
{
  "data": [
    {
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
    },
    {
      "id": "9",
      "type": "roles",
      "links": {
        "self": "http://api.teamtailor.dev/v1/roles/9"
      },
      "attributes": {
        "name": "Developer"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/roles/9/relationships/department",
            "related": "http://api.teamtailor.dev/v1/roles/9/department"
          }
        }
      }
    },
    {
      "id": "50",
      "type": "roles",
      "links": {
        "self": "http://api.teamtailor.dev/v1/roles/50"
      },
      "attributes": {
        "name": "Product owner"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/roles/50/relationships/department",
            "related": "http://api.teamtailor.dev/v1/roles/50/department"
          }
        }
      }
    },
    {
      "id": "2106",
      "type": "roles",
      "links": {
        "self": "http://api.teamtailor.dev/v1/roles/2106"
      },
      "attributes": {
        "name": "Pre-sales"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/roles/2106/relationships/department",
            "related": "http://api.teamtailor.dev/v1/roles/2106/department"
          }
        }
      }
    },
    {
      "id": "2107",
      "type": "roles",
      "links": {
        "self": "http://api.teamtailor.dev/v1/roles/2107"
      },
      "attributes": {
        "name": "Field sales"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/roles/2107/relationships/department",
            "related": "http://api.teamtailor.dev/v1/roles/2107/department"
          }
        }
      }
    },
    {
      "id": "2108",
      "type": "roles",
      "links": {
        "self": "http://api.teamtailor.dev/v1/roles/2108"
      },
      "attributes": {
        "name": "Sales Manager"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/roles/2108/relationships/department",
            "related": "http://api.teamtailor.dev/v1/roles/2108/department"
          }
        }
      }
    },
    {
      "id": "1",
      "type": "roles",
      "links": {
        "self": "http://api.teamtailor.dev/v1/roles/1"
      },
      "attributes": {
        "name": "Copywriter"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/roles/1/relationships/department",
            "related": "http://api.teamtailor.dev/v1/roles/1/department"
          }
        }
      }
    },
    {
      "id": "2",
      "type": "roles",
      "links": {
        "self": "http://api.teamtailor.dev/v1/roles/2"
      },
      "attributes": {
        "name": "PR Manager"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/roles/2/relationships/department",
            "related": "http://api.teamtailor.dev/v1/roles/2/department"
          }
        }
      }
    },
    {
      "id": "3",
      "type": "roles",
      "links": {
        "self": "http://api.teamtailor.dev/v1/roles/3"
      },
      "attributes": {
        "name": "Online Marketeer"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/roles/3/relationships/department",
            "related": "http://api.teamtailor.dev/v1/roles/3/department"
          }
        }
      }
    }
  ],
  "meta": {
    "record-count": 9,
    "page-count": 1
  },
  "links": {
    "first": "http://api.teamtailor.dev/v1/roles?page%5Bnumber%5D=1&page%5Bsize%5D=10",
    "last": "http://api.teamtailor.dev/v1/roles?page%5Bnumber%5D=1&page%5Bsize%5D=10"
  }
}
```
