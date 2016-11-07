## Show a Job

```http
GET https://api.teamtailor.com/v1/jobs/{id} HTTP/1.1
Authorization: Token token=abc123abc123
```

```shell
curl -X "GET" "https://api.teamtailor.com/v1/jobs/{id}" \
     -H "Authorization: Token token=abc123abc123"
```

> Example response

```json
{
  "data": {
    "id": "7199",
    "type": "jobs",
    "links": {
      "careersite-job-url": "http://career.teamtailor.dev/jobs/7263-yay-horray-3",
      "careersite-job-apply-url": "https://career.teamtailor.dev/jobs/7263-yay-horray-3/applications/new",
      "self": "http://api.teamtailor.dev/v1/jobs/7263"
    },
    "attributes": {
      "ask-for-cover-letter": true,
      "ask-for-resume": true,
      "body": "<p>hello world</p>",
      "end-date": null,
      "external-application-url": null,
      "human-status": "published",
      "picture": null,
      "pinned": false,
      "start-date": null,
      "status": "open",
      "template": false,
      "title": "My new job"
    },
    "relationships": {
      "department": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7263/relationships/department",
          "related": "http://api.teamtailor.dev/v1/jobs/7263/department"
        }
      },
      "role": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7263/relationships/role",
          "related": "http://api.teamtailor.dev/v1/jobs/7263/role"
        }
      },
      "location": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7263/relationships/location",
          "related": "http://api.teamtailor.dev/v1/jobs/7263/location"
        }
      },
      "user": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7263/relationships/user",
          "related": "http://api.teamtailor.dev/v1/jobs/7263/user"
        }
      }
    }
  }
}
```

Show one job

Parameter | Description
--------- | -----------
id        | The job's id.
