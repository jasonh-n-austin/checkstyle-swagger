Obviously I haven't worked on this project/PoC in a long time. 
If you're looking for this kind of functionality, the problem has been solved with [Stoplight's Spectral](https://stoplight.io/open-source/spectral/)

# swagger-api-checkstyle
Defines conventions for Swagger definitions for API governance

In microservice environments, the ability to validate designs for consistency with platform standards is critically imporant.

Some areas of concern in governing standards:
* Naming conventions of paths, parameters, and operationIds
* Restrict the use of verb, status
* Enforce the use of schema and formats in parameters and fields

`swagger-api-checkstyle` is a specification meant to designate these governance criteria. This should provide a specification for implementing the validation of API spec files against a checkstyle definition.

Node library in development

