### Implementation notes

I've decided to use an HTTP REST API for this set of services over other implementation approaches such as a GraphQL 
based API since having high levels of flexibility for querying these systems doesn't seem to be a key requirement given 
the current use-cases. Also, an HTTP based integration for an SDK will reduce the number of libraries that
will need to be bundled in it.

### Requirements

- docker
- docker-compose

### API docs

In the root directory of this project execute `docker-compose up -d` to run the docker containers with redoc

Navigate to [localhost:8080](http://localhost:8080) to access Checkout Service API documentation
Navigate to [localhost:8081](http://localhost:8081) to access Shipping Service API documentation
Navigate to [localhost:8081](http://localhost:8082) to access Payment Service API documentation

### Notes

Functionality not implemented

- Delete a shopping cart
- Update or delete a shipping method in the shopping cart
- Update or delete a payment method in the shopping cart
- Create, update or delete a shipping method
- Create, update or delete a payment method
