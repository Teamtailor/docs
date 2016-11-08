# Versioning

```http
GET http://api.teamtailor.dev/v1/jobs HTTP/1.1
Authorization: Token token=abc123abc123
X-Api-Version: 2016-10-01
```

```shell
curl -X "GET" "http://api.teamtailor.dev/v1/jobs/7199" \
     -H "Authorization: Token token=abc123abc123" \
     -H "Api-Version: 2016-10-01"
```

When we make backwards-incompatible changes to the API, we release new, dated versions.

To set the API version on a specific request, send a Teamtailor-Version header.

Check the API changelog to see current and old versions
