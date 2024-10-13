# Healthcheck implementation details

`GET` request to `/health_check` shoud return a `200 status` response if the service is successfully running else return a `301 status` response.