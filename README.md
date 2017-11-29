# datasets-api-gateway
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Filikebits%2Fdatasets-api-gateway.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Filikebits%2Fdatasets-api-gateway?ref=badge_shield)


An example server application for handling requests to the Mapbox Datasets API.

## Running

Required environment variables:

* `MapboxAccessToken`: an access token with datasets:read and datasets:write
  scopes.
* `MapboxDatasetID`: the ID of the wrapped dataset.

Optional variables for access control:

* `JWT_REQUIRED_FOR`: can be `read`, `read,write`, or nothing
* `JWT_SECRET`: see [express-jwt](https://github.com/auth0/express-jwt) for documentation.
* `JWT_AUDIENCE`: see [express-jwt](https://github.com/auth0/express-jwt) for documentation.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Filikebits%2Fdatasets-api-gateway.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Filikebits%2Fdatasets-api-gateway?ref=badge_large)