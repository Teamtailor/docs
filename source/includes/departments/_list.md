## List departments

```http
GET https://api.teamtailor.com/v1/departments HTTP/1.1
Authorization: Token token=abc123abc123
```

```shell
curl -X "GET" "https://api.teamtailor.com/v1/departments" \
     -H "Authorization: Token token=abc123abc123"
```

> Example response

```json
{
  "data": [
    {
      "id": "337",
      "type": "departments",
      "links": {
        "self": "http://api.teamtailor.dev/v1/departments/337"
      },
      "attributes": {
        "name": "Product Developments",
        "people-headline": "hello people",
        "people-text": "<p>this is us</p>",
        "row-order": -4194303,
        "start-page-headline": "Building the future.",
        "start-page-text": "We know how to build great products. We have built products used by over 5000 companies in the nordics. We are a small team of senior and junior product builders. We live and breath Ruby on rails. We are always looking for smart & fun people so don't be a stranger. Contact us today.",
        "pictures": [
          {
            "standard": "https://res.cloudinary.com/teamtailor-development/image/upload/c_fill,f_auto,g_faces:center,h_465,q_80,w_930/v1422365162/f3kp2yz3wickhtqrb50s.jpg"
          }
        ]
      },
      "relationships": {
        "roles": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/departments/337/relationships/roles",
            "related": "http://api.teamtailor.dev/v1/departments/337/roles"
          }
        }
      }
    },
    {
      "id": "338",
      "type": "departments",
      "links": {
        "self": "http://api.teamtailor.dev/v1/departments/338"
      },
      "attributes": {
        "name": "Sales and stuff",
        "people-headline": "",
        "people-text": "",
        "row-order": 1572865,
        "start-page-headline": "Users, users & users.",
        "start-page-text": "Our objective is to identify and convert HR/Marketing professionals to become Teamtailor users. The good thing is that we know we are selling a great product, makes our jobs fun. We don't believe in sell as hell at all cost. Its about educating our users and once they understand the power of the webb/social media they want to become users. Join us.",
        "pictures": [
          {
            "standard": "https://res.cloudinary.com/teamtailor-development/image/upload/c_fill,f_auto,g_faces:center,h_465,q_80,w_930/v1422369190/mqv02tchequezical6ue.jpg"
          }
        ]
      },
      "relationships": {
        "roles": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/departments/338/relationships/roles",
            "related": "http://api.teamtailor.dev/v1/departments/338/roles"
          }
        }
      }
    },
    {
      "id": "339",
      "type": "departments",
      "links": {
        "self": "http://api.teamtailor.dev/v1/departments/339"
      },
      "attributes": {
        "name": "Marketing & PR",
        "people-headline": "",
        "people-text": "",
        "row-order": 7340032,
        "start-page-headline": "Spread the word.",
        "start-page-text": "Do you want to help us spread the word of modern & effective recruting? We are on to something but we need others to know it as well. Help us make the HR/Marketing world a happier place!",
        "pictures": [
          {
            "standard": "https://res.cloudinary.com/teamtailor-development/image/upload/c_fill,f_auto,g_faces:center,h_465,q_80,w_930/v1422370235/mbdlqjzneliyy0l5kcjn.jpg"
          }
        ]
      },
      "relationships": {
        "roles": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/departments/339/relationships/roles",
            "related": "http://api.teamtailor.dev/v1/departments/339/roles"
          }
        }
      }
    }
  ],
  "meta": {
    "record-count": 3,
    "page-count": 1
  },
  "links": {
    "first": "http://api.teamtailor.dev/v1/departments?page%5Bnumber%5D=1&page%5Bsize%5D=10",
    "last": "http://api.teamtailor.dev/v1/departments?page%5Bnumber%5D=1&page%5Bsize%5D=10"
  }
}
```