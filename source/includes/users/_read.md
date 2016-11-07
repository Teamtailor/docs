## Show an User

```http
GET https://api.teamtailor.com/v1/users/4468 HTTP/1.1
Authorization: Token token=abc123abc123
```

```shell
curl -X "GET" "https://api.teamtailor.com/v1/users/4468" \
     -H "Authorization: Token token=abc123abc123"
```

> Example response

```json
{
  "data": {
    "id": "4468",
    "type": "users",
    "links": {
      "self": "http://api.teamtailor.dev/v1/users/4468"
    },
    "attributes": {
      "description": "<p>test</p>",
      "email": "jonas@teamtailor.com",
      "facebook-profile": "https://www.facebook.com/himynameisjonas",
      "google-profile": "",
      "hide-email": false,
      "instagram-profile": "http://instagram.com/himynameisjonas",
      "linkedin-profile": "https://www.linkedin.com/in/himynameisjonas",
      "name": "Jonas Brusman",
      "other-profile": "http://himynameisjonas.net",
      "phone": "",
      "picture": {
        "standard": "https://res.cloudinary.com/teamtailor-development/image/upload/c_fill,dpr_2.0,f_auto,g_faces:center,h_160,q_80,w_160/v1423832344/hbwennnqa7uo7kubkzry.jpg"
      },
      "role": "admin",
      "title": "Developer",
      "twitter-profile": "https://twitter.com/himynameisjonas",
      "username": "jonas5",
      "visible": true
    },
    "relationships": {
      "department": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/users/4468/relationships/department",
          "related": "http://api.teamtailor.dev/v1/users/4468/department"
        }
      },
      "location": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/users/4468/relationships/location",
          "related": "http://api.teamtailor.dev/v1/users/4468/location"
        }
      }
    }
  }
}
```