#  Swagger PetStore - open API 3.0 Integration sample

## Description
This sample implements 'Petstore' API according to the example 'Petstore' Swagger definition on https://editor.swagger.io/#.  We provide examples how to use the Linx RESTHost to call REST Web services.  The sample has been publisehd on the Linx demo server, the Swagger documentation is available [here](https://demo.api.linx.twenty57.net/petstore/swagger).  

## Installation
The below steps describe how to host this Solution on your own Linx cloud server environment.

- For this sample, the api key **special-key** is used to test the authorization filters. 
- Register for a Linx trial server. You will receive an email containing your Linx cloud servera and drive space.
This solution runs on a Linx cloud server instance and integrates with swagger-petstore.  The swagger-petstore is a java project to build a stand-alone server which implements the OpenAPI 3 Spec. You can find out more about both the spec and the framework at http://swagger.io.  


## Usage
***1. Test with Postman***
****Configure Postman collection:****
1. Open Postman and import the provided request collection in Postman.
2. The sample has been publisehd on the Linxdemo server **https://demo.linx.twenty57.net/petstore**.  
3. Open each request and pass parameters and body values as described in `https://petstore3.swagger.io/`

***2. Test with Swagger documentation***

The test can be done on https://demo.api.linx.twenty57.net/petstore/swagger

***Aspects of the Open API 3 specification which are not supported by the RESTHost:***
1. RequestBodies
2. SecuritySchemes and OAuth

## Contributing

For questions please ask the [Linx community](https://linx/software/community) or use the [Slack channel](https://linxsoftware.slack.com/archives/C01FLBC1XNX). 

## License

[MIT](https://github.com/linx-software/template-repo/blob/main/LICENSE.txt)
