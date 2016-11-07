## Update Job

```http
PATCH https://api.teamtailor.com/v1/jobs/7199 HTTP/1.1
Authorization: Token token=abc123abc123

{
  "data": {
    "id": "7199",
    "attributes": {
      "title": "New Title",
      "status": "unlisted"
    },
    "type": "jobs"
  }
}
```

```shell
curl -X "PATCH" "https://api.teamtailor.com/v1/jobs/7199" \
     -H "Authorization: Token token=abc123abc123" \
     -H "Content-Type: application/vnd.api+json" \
     -d "{\"data\":{\"id\":\"7199\",\"attributes\":{\"title\":\"New Title\",\"status\":\"unlisted\"},\"type\":\"jobs\"}}"
```

> Example response

```json
{
  "data": {
    "id": "7199",
    "type": "jobs",
    "links": {
      "careersite-job-url": "http://career.teamtailor.dev/jobs/7199-yay-horray",
      "careersite-job-apply-url": "https://career.teamtailor.dev/jobs/7199-yay-horray/applications/new",
      "self": "http://api.teamtailor.dev/v1/jobs/7199"
    },
    "attributes": {
      "ask-for-cover-letter": true,
      "ask-for-resume": true,
      "body": "<p>lopl</p>",
      "end-date": null,
      "external-application-url": "",
      "human-status": "published",
      "picture": null,
      "pinned": false,
      "start-date": null,
      "status": "open",
      "template": false,
      "title": "yay horray"
    },
    "relationships": {
      "department": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7199/relationships/department",
          "related": "http://api.teamtailor.dev/v1/jobs/7199/department"
        }
      },
      "role": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7199/relationships/role",
          "related": "http://api.teamtailor.dev/v1/jobs/7199/role"
        }
      },
      "location": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7199/relationships/location",
          "related": "http://api.teamtailor.dev/v1/jobs/7199/location"
        }
      },
      "user": {
        "links": {
          "self": "http://api.teamtailor.dev/v1/jobs/7199/relationships/user",
          "related": "http://api.teamtailor.dev/v1/jobs/7199/user"
        }
      }
    }
  }
}
```

Update job
