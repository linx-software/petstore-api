#  Swagger PetStore - open API 3.0 Integration sample

## Description
This sample implements 'Petstore' API according to the example 'Petstore' Swagger definition on https://editor.swagger.io/#.  We provide examples how to use the Linx RESTHost to call REST Web services.  The sample has been published on the demo server but it can also be run on a local machine or local server.  

## Installation
For this sample, the api key **special-key** is used to test the authorization filters. 

## Usage
***Configure Postman collection:*** 
1. Open Postman and import the provided request collection in Postman.
2. The sample has been publisehd on the Linxdemo server **https://demo.linx.twenty57.net/petstore**.  
3. Open each request and pass parameters and body values as described in `https://petstore3.swagger.io/`

**Some exceptions and limitations:**
Aspects of the Open API 3 specification which are not supported by the RESTHost:
1. RequestBodies
2. SecuritySchemes and OAuth


## Contributing

For questions please ask the [Linx community](https://linx/software/community) or use the [Slack channel](https://linxsoftware.slack.com/archives/C01FLBC1XNX). 

## License

[MIT](https://github.com/linx-software/template-repo/blob/main/LICENSE.txt)
