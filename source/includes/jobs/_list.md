## List Jobs

```shell
GET http://api.teamtailor.dev/v1/jobs
```

> The above command returns JSON structured like this:

```json
{
  "data": [
    {
      "id": "7263",
      "type": "jobs",
      "links": {
        "careersite-job-url": "http://career.teamtailor.dev/jobs/7263-yay-horray-3",
        "careersite-job-apply-url": "https://career.teamtailor.dev/jobs/7263-yay-horray-3/applications/new",
        "self": "http://api.teamtailor.dev/v1/jobs/7263"
      },
      "attributes": {
        "ask-for-cover-letter": true,
        "ask-for-resume": true,
        "body": "hello",
        "end-date": null,
        "external-application-url": null,
        "human-status": "published",
        "picture": null,
        "pinned": false,
        "start-date": null,
        "status": "open",
        "template": false,
        "title": "yay horray 3"
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
    },
    {
      "id": "7262",
      "type": "jobs",
      "links": {
        "careersite-job-url": "http://career.teamtailor.dev/jobs/7262-yay-horray-3",
        "careersite-job-apply-url": "https://career.teamtailor.dev/jobs/7262-yay-horray-3/applications/new",
        "self": "http://api.teamtailor.dev/v1/jobs/7262"
      },
      "attributes": {
        "ask-for-cover-letter": true,
        "ask-for-resume": true,
        "body": "hello",
        "end-date": null,
        "external-application-url": null,
        "human-status": "published",
        "picture": null,
        "pinned": false,
        "start-date": null,
        "status": "open",
        "template": false,
        "title": "yay horray 3"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/jobs/7262/relationships/department",
            "related": "http://api.teamtailor.dev/v1/jobs/7262/department"
          }
        },
        "role": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/jobs/7262/relationships/role",
            "related": "http://api.teamtailor.dev/v1/jobs/7262/role"
          }
        },
        "location": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/jobs/7262/relationships/location",
            "related": "http://api.teamtailor.dev/v1/jobs/7262/location"
          }
        },
        "user": {
          "links": {
            "self": "http://api.teamtailor.dev/v1/jobs/7262/relationships/user",
            "related": "http://api.teamtailor.dev/v1/jobs/7262/user"
          }
        }
      }
    }
  ],
  "meta": {
    "record-count": 2,
    "page-count": 1
  },
  "links": {
    "first": "http://api.teamtailor.dev/v1/jobs?filter%5Bdepartment%5D=337&page%5Bnumber%5D=1&page%5Bsize%5D=10",
    "last": "http://api.teamtailor.dev/v1/jobs?filter%5Bdepartment%5D=337&page%5Bnumber%5D=1&page%5Bsize%5D=10"
  }
}
```

This endpoint retrieves all kittens.

Parameter | Default | Description
--------- | ------- | -----------
include   | null    | Comma separated list of relations to include in the response.
filter[status] | null | Filter by job status. Available statuses: `Published`.