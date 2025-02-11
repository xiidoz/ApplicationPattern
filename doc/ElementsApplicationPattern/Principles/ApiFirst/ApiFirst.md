# API-First Approach

The API-first approach involves developing APIs that are consistent and reusable, which can be accomplished by using an API description language to establish a contract for how the API is supposed to behave.  
One of the most popular API description languages is OpenAPI specification (OAS 3, formerly called Swagger).  
Establishing a contract involves spending more time thinking about the design of an API.  
It also often involves additional planning and collaboration with the stakeholders providing feedback on the design of an API before any code is written.  

An API specification explains how the API functions and the results to expect when using the API.  
When properly defined, a developer can understand the requirements, generate stub from the specification, implement the business logic and deploy the implemented application.  
Also, by using this specification, test suites stubs can be generated which can be further complemented to automate the application testing.  

In the MW SDN implementation of the API-first approach, the ApplicationOwner is writing an API specification document in OAS3 syntax.  
The ApplicationOwner is supported by a template, which already contains a wide set of basic functions that have to be supported by all applications that are planned to become parts of the MW SDN application layer.  
Chapter [Specifying Applications](../../../SpecifyingApplications/SpecifyingApplications.md) supports harmonizing specifications for proper integration of the resulting implementations into the application layer.  
After review by the team of ApplicationOwners, the API specification will be frozen and published for ApplicationImplementers to offer implementing it.  
So, in this appliance of the API-first approach the specification represents even a commercially relevant contract between specification and implementation.  


_Further reading:_  
_https://swagger.io/resources/articles/adopting-an-api-first-approach/_  
_https://swagger.io/specification/_  
