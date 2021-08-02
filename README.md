#  Swagger PetStore - open API 3.0 Integration sample

## Description
This sample implements 'Petstore' API according to the example 'Petstore' Swagger definition on https://editor.swagger.io/#. Petstore swagger is a sample server Petstore server. The swagger-petstore is a java project to build a stand-alone server which implements the OpenAPI 3 Spec. You can find out more about both the spec and the framework at http://swagger.io.  In this sample, we provide examples how to use the **Linx RESTHost** to call swagger PETStore REST Web services.  The sample has been published on the [Linx demo server](https://demo.linx.twenty57.net/), the Linx Swagger documentation is available [here](https://demo.api.linx.twenty57.net/petstore/swagger).  

## Installation
The below steps describe how to host this Solution on your own Linx cloud server environment.
- Linx Designer - download it [here](https://linx.software/)
- Open the sample Solution (.lsoz) in your Linx Designer.

Listed below are the usage steps involved in using the deployed service from 2 request platforms:
- For this sample, the api key **special-key** is used to test the authorization filters. 
- Register for a Linx trial server. You will receive an email containing your Linx cloud server and a drive space.
This solution runs on a Linx cloud server instance and integrates with swagger-petstore.  


## Usage
***1. Test with Swagger documentation***
[View live demo on Swagger](https://demo.api.linx.twenty57.net/petstore/swagger)

***2. Test with Postman***
****Configure Postman collection:****
The attached postman collection is all set to send request the demo server.
1. Open Postman and import the provided request collection in Postman.
2. The sample has been publisehd on the Linxdemo server **https://demo.linx.twenty57.net/petstore**.  
3. Open each request and pass or change parameters and body values as described in `https://petstore3.swagger.io/`

***3. Test on local machine or any other server apart from the demo server***

The solution can be deployed on your local machine or any other server.  
1. Change the following values in the settings:
    - `LinxApiBaseUri` : Base uri of host machine
    - `LinxApiPort` : port
    - `LinxIsLocalDevEnv` : true or false. 
    - `LinxServerHostname` : host name

## Contributing

For questions please ask the [Linx community](https://linx/software/community) or use the [Slack channel](https://linxsoftware.slack.com/archives/C01FLBC1XNX). 

## License

[MIT](https://github.com/linx-software/template-repo/blob/main/LICENSE.txt)
