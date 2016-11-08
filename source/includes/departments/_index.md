# Departments

## Department Object

```json
{
  "data": {
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
  }
}
```

### Attributes

Attribute           | Type    | Description
--------------------|---------|------------
name                | string  | The departmen's name
people-headline     | string  | Headline for the people block
people-text         | string  | Text for the people block
row-order           | integer | Value used for sorting, lowest first.
start-page-headline | string  | Description headline
start-page-text     | string  | Description text
pictures            | object  | Array of pictures

### Relations

Relation | Description
---------|------------
roles    | The department's roles
