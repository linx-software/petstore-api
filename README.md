#  Swagger PetStore - open API 3.0 Integration sample

## Description
This sample implements a Linx REST API based on the Swagger 'Petstore' Open API definition and hosted on a Linx Cloud Server, more details on the original 'Petstore' GitHub project can be found [here](https://github.com/swagger-api/swagger-petstore). The operations of the Linx API do not persist any data, but rather, request data is forwarded to actual 'Petstore' server via HTTP requests.  

View the [live demo](https://demo.api.linx.twenty57.net/petstore/swagger) hosted on a Linx Cloud Server.


## Installation

### Cloud server deployment
This solution can be deployed directly to your Linx Cloud server instance.

1. Register for a Linx trial cloud server [here](https://linx.software/server-buy2/).
2. You will receive an email containing your Linx cloud server credentials when your trial server has been activated.
1. Log into your cloud server instance and upload the Solution (Top Menu > Server > Upload).
3. On the Solution's service dashboard page, __start__ all of the services for the Solution.   
4. Once the service has started, you are able to make requests using the base URL of:
   ```
   https://{your instance name}.api.linx.twenty57.net/petstore
   ```


### Local environment
The below steps describe how to setup the sample to run on your local Linx Designer environment.

1. Download and install the Linx Designer [here](https://linx.software/server-buy2/).
1. Open the sample Solution (.lsoz) in your Linx Designer.
2. Alter the below Solution Settings:
    - `LinxIsLocalDevEnv` : `False`
3. Select the RESTHost service, right click and select __debug__. Once initialised, **start** the debugger.
4. Once the debugger has started, you are able to make requests locally to:
   ```
   https://localhost:8080/petstore
   ```

## Usage

### Swagger UI
[View live demo](https://demo.api.linx.twenty57.net/petstore/swagger).


### Postman
1. Open Postman and import the provided [request collection](https://github.com/linx-software/petstore-api/blob/main/tests/postman-collection/Swagger%20Petstore%20with%20Linx.postman_collection.json) in Postman.
2. Alter the collection variables to reflect your cloud environment.
 
3. Open each request and pass or change parameters and body values as described in `https://petstore3.swagger.io/`



## Contributing

For questions please ask the [Linx community](https://linx/software/community) or use the [Slack channel](https://linxsoftware.slack.com/archives/C01FLBC1XNX). 

## License

[MIT](https://github.com/linx-software/template-repo/blob/main/LICENSE.txt)
