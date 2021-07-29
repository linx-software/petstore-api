# PetStore integration

## Description
This sample implement 'Petstore' API according to the example 'Petstore' Swagger definition: https://editor.swagger.io/#.  We've not icluded the securitySchemes/oauth. 

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
2. securitySchemes/oauth


## Contributing

For questions please ask the [Linx community](https://linx/software/community) or use the [Slack channel](https://linxsoftware.slack.com/archives/C01FLBC1XNX). 

## License

[MIT](https://github.com/linx-software/template-repo/blob/main/LICENSE.txt)
