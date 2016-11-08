# Versioning

> Headers

```http
GET https://api.teamtailor.com/v1/jobs?filter%5Bdepartment%5D=337 HTTP/1.1
X-Api-Version : 20161108
```

```shell
curl -X "GET" "https://api.teamtailor.com/v1/jobs?filter%5Bdepartment%5D=337" \
     -H "X-Api-Version: 20161108"
```

When we make backwards-incompatible changes to the API, we release new, dated versions.

To set the API version on a specific request, send a Teamtailor-Version header.

Check the API changelog to see current and old versions