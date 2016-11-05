# Rate Limit

There is currently no rate-limit for the API. But when implemented it will use the following headers: 

* X-Rate-Limit-Limit - The number of allowed requests in the current period
* X-Rate-Limit-Remaining - The number of remaining requests in the current period
* X-Rate-Limit-Reset - The number of seconds left in the current period

The headers are already present in every response but contains static values. 
