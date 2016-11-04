## List Jobs

```shell
curl "https://api.teamtailor.com/v1/api/jobs"
```

> The above command returns JSON structured like this:

```json
{
  "data": [
    {
      "id": "7158",
      "type": "jobs",
      "links": {
        "careersite-job-url": "https://career.teamtailor.com/jobs/7158-detta-ar-en-template",
        "careersite-job-apply-url": "https://career.teamtailor.com/jobs/7158-detta-ar-en-template/applications/new",
        "self": "https://api.teamtailor.com/v1/jobs/7158"
      },
      "attributes": {
        "ask-for-cover-letter": true,
        "ask-for-resume": false,
        "body": "<p>här här <strong>template</strong> bodyn</p>",
        "end-date": null,
        "external-application-url": null,
        "human-status": "published",
        "picture": null,
        "pinned": false,
        "start-date": null,
        "status": "open",
        "template": true,
        "title": "detta är en template"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "https://api.teamtailor.com/v1/jobs/7158/relationships/department",
            "related": "https://api.teamtailor.com/v1/jobs/7158/department"
          }
        },
        "role": {
          "links": {
            "self": "https://api.teamtailor.com/v1/jobs/7158/relationships/role",
            "related": "https://api.teamtailor.com/v1/jobs/7158/role"
          }
        },
        "location": {
          "links": {
            "self": "https://api.teamtailor.com/v1/jobs/7158/relationships/location",
            "related": "https://api.teamtailor.com/v1/jobs/7158/location"
          }
        },
        "user": {
          "links": {
            "self": "https://api.teamtailor.com/v1/jobs/7158/relationships/user",
            "related": "https://api.teamtailor.com/v1/jobs/7158/user"
          }
        }
      }
    },
    {
      "id": "1694",
      "type": "jobs",
      "links": {
        "careersite-job-url": "https://career.teamtailor.com/jobs/1694-web-developer-with-fingerspitzengefuhll",
        "careersite-job-apply-url": "https://career.teamtailor.com/jobs/1694-web-developer-with-fingerspitzengefuhll/applications/new",
        "self": "https://api.teamtailor.com/v1/jobs/1694"
      },
      "attributes": {
        "ask-for-cover-letter": true,
        "ask-for-resume": true,
        "body": "<p>\r\n\tTeamtailor is changing the way companies work with employer branding and recruiting online. Want to help us make HR heroes? Working at Teamtailor means working in a young, fast moving tech startup and working with smart people that are passionate about their work.</p><p>\r\n\t<span style=\"line-height: 1.45em; background-color: initial;\">Our team brings experience from companies such as Skype and Mynewsdesk. We have disrupted and transformed industries before. We already got revenues and are well funded.</span></p><p>\r\n\t        Read more about our product at \r\n\t<a href=\"https://teamtailor.com/\" target=\"_blank\">teamtailor.com</a>. Or why not look at som live examples: <a href=\"https://jobs.rebtel.com/\" target=\"_blank\">Rebtel</a>, <a href=\"https://jobb.fyndiq.se/\" target=\"_blank\">Fyndiq</a>, <a href=\"https://career.cybercom.com/\" target=\"_blank\">Cybercom</a>, <a href=\"https://epidemic-sound.teamtailor.com/\" target=\"_blank\">Epidemic sound</a> (yes, everything you see there is our product and yes it's amazing).</p><p>\r\n\t<strong>What is the role?</strong><br>\r\n\t        At the core, you will be part of the team that plans new features, and develops the product. You will also take part in planning the roadmap, talking to the customers, and be a part of building a world class team.</p><p>\r\n\t<strong>What skills do you need? <br>\r\n\t</strong>Being a start-up, we still have a lot of ground to cover and big questions to answer. Given that, we’re looking for someone that thrives when faced with complex problems, and likes to think outside the box (...what box b.t.w?).</p><p>\r\n\t                 Teamtailor is a Ruby on Rails app. Other key components in our current setup is postgresql, elasticsearch, redis. Previous relevant experience is a great, but we value the ability to learn new things over past experience.</p><p>\r\n\t<strong>Qualities we look for</strong></p><ul>\r\n\t<li>Fingerspitzengefühl. For every challenge there is a infinite number of possible solutions, you should have a talent for finding the best one.</li>\t<li>Eager to learn new things. The only thing we know is that a lot of things will change. Both the tech we use, but also about the industry we operate in. </li>\t<li>Passionate. We love what we do, you should too.</li>\r\n</ul><p>\r\n\t      Interested? Apply today. Or if you know someone that you think would like this opportunity let us know.</p>",
        "end-date": null,
        "external-application-url": "",
        "human-status": "published",
        "picture": {
          "standard": "https://res.cloudinary.com/teamtailor-development/image/upload/c_lfill,f_auto,g_faces:center,h_400,q_80,w_1200/v1478092951/xxbzay6ykdurddlazhys.jpg",
          "thumb": "https://res.cloudinary.com/teamtailor-development/image/upload/c_lfill,f_auto,g_faces:center,h_300,q_80,w_400/v1478092951/xxbzay6ykdurddlazhys.jpg"
        },
        "pinned": false,
        "start-date": null,
        "status": "open",
        "template": false,
        "title": "Web developer with fingerspitzengefühll"
      },
      "relationships": {
        "department": {
          "links": {
            "self": "https://api.teamtailor.com/v1/jobs/1694/relationships/department",
            "related": "https://api.teamtailor.com/v1/jobs/1694/department"
          }
        },
        "role": {
          "links": {
            "self": "https://api.teamtailor.com/v1/jobs/1694/relationships/role",
            "related": "https://api.teamtailor.com/v1/jobs/1694/role"
          }
        },
        "location": {
          "links": {
            "self": "https://api.teamtailor.com/v1/jobs/1694/relationships/location",
            "related": "https://api.teamtailor.com/v1/jobs/1694/location"
          }
        },
        "user": {
          "links": {
            "self": "https://api.teamtailor.com/v1/jobs/1694/relationships/user",
            "related": "https://api.teamtailor.com/v1/jobs/1694/user"
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
    "first": "https://api.teamtailor.com/v1/jobs?filter%5Bdepartment%5D=337&page%5Bnumber%5D=1&page%5Bsize%5D=10",
    "last": "https://api.teamtailor.com/v1/jobs?filter%5Bdepartment%5D=337&page%5Bnumber%5D=1&page%5Bsize%5D=10"
  }
}
```

This endpoint retrieves all kittens.

Parameter | Default | Description
--------- | ------- | -----------
include   | null    | Comma separated list of relations to include in the response.
filter[status] | null | Filter by job status. Available statuses: `Published`.
