# Rate Limit

> Headers

```shell
X-Rate-Limit-Limit
# The number of allowed requests in the current period

X-Rate-Limit-Remaining
# The number of remaining requests in the current period

X-Rate-Limit-Reset
# The number of seconds left in the current period
```

The headers are already present in every response but contains static values. Please use common sense when making requests to the API until it returns real rate limit values.
