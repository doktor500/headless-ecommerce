### Implementation notes

I've decided to use an HTTP REST API for this set of services over other implementation approaches such as a GraphQL 
based API since having high levels of flexibility for querying these systems doesn't seem to be a key requirement given 
the current use-cases. Also, an HTTP based integration for an SDK will reduce the number of libraries that
will need to be bundled in it.

### Requirements

- docker
- docker-compose

### API docs

- [Checkout service Api Docs](checkout-service/docs/api/README.md)
- [Shipping service Api Docs](shipping-service/docs/api/README.md)
