## Create Job

```http
POST https://api.teamtailor.com/v1/jobs HTTP/1.1
Authorization: Token token=abc123abc123

{
  "data": {
    "type": "jobs",
    "attributes": {
      "title": "Account Manager",
      "body": "<p>hello</p>"
    },
    "relationships": {
      "user": {
        "data": {
          "id": "819",
          "type": "users"
        }
      },
      "department": {
        "data": {
          "id": "337",
          "type": "departments"
        }
      },
      "location": {
        "data": {
          "id": "667",
          "type": "locations"
        }
      }
    }
  }
}

```

```shell
curl -X "POST" "https://api.teamtailor.com/v1/jobs" \
     -H "Authorization: Token token=abc123abc123" \
     -H "Content-Type: application/vnd.api+json" \
     -d "{\"data\":{\"type\":\"jobs\",\"attributes\":{\"title\":\"Account Manager\",\"body\":\"<p>hello</p>\"},\"relationships\":{\"user\":{\"data\":{\"id\":\"819\",\"type\":\"users\"}},\"department\":{\"data\":{\"id\":\"337\",\"type\":\"departments\"}},\"location\":{\"data\":{\"id\":\"667\",\"type\":\"locations\"}}}}}"
```

> Example response

```json
{
  "data": {
    "id": "7265",
    "type": "jobs",
    "links": {
      "careersite-job-url": "http://career.teamtailor.dev/jobs/7265-account-manager",
      "careersite-job-apply-url": "https://career.teamtailor.dev/jobs/7265-account-manager/applications/new",
      "self": "http://api.teamtailor.dev/v1/jobs/7265"
    },
    "attributes": {
      "ask-for-cover-letter": true,
      "ask-for-resume": true,
      "body": "<p>hello</p>",
      "end-date": null,
      "external-application-url": null,
      "human-status": "published",
      "picture": null,
      "pinned": false,
      "start-date": null,
      "status": "open",
      "template": false,
      "title": "Account Manager"
    },
    "relationships": {
      "department": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7265/relationships/department",
          "related": "http://api.teamtailor.dev/v1/jobs/7265/department"
        }
      },
      "role": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7265/relationships/role",
          "related": "http://api.teamtailor.dev/v1/jobs/7265/role"
        }
      },
      "location": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7265/relationships/location",
          "related": "http://api.teamtailor.dev/v1/jobs/7265/location"
        }
      },
      "user": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7265/relationships/user",
          "related": "http://api.teamtailor.dev/v1/jobs/7265/user"
        }
      }
    }
  }
}
```

Create new jobs and stuff.
