![OpenAPI Logo](http://ar-logistics-hk-prod.oss-cn-hongkong.aliyuncs.com/logistics-parent/openapi/DJYClogo.png?x-oss-process=image/resize,p_8) GIGALogistics OpenAPI Definition
==============================================

This repo contains the official [OpenAPI 3.0](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.2.md) definitions for the [GIGALogistics API](https://heyoushan66.github.io/onepiece).  You can use these definitions with any of countless [OpenAPI tools](https://openapi.tools/) to generate sample code, tests, mock servers, etc.


Which file to use
-----------------------------------
Depending on your preferences and/or tooling, you may choose to use one or more of the following files:

|Path                |Description
|:-------------------|:--------------------------------
|[`openapi.yaml`](openapi.yaml)        |The entire GIGALOGISTICS OpenAPI definition, in a single YAML file.  This file uses [`$ref` pointers](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.2.md#reference-object) to reduce duplication and keep the file small and fairly human-readable.<br><br> Some [OpenAPI tools](https://openapi.tools/) don't support YAML or don't support `$ref` pointers, so you may need to use the [`openapi.json` file](openapi.json) instead.
|[`openapi.json`](openapi.json)        |The entire GIGALOGISTICS OpenAPI definition, in a single JSON file.  This file **does not** contain any `$ref` pointers, which means it should work with any [OpenAPI tool](https://openapi.tools/).


Other API Definition Formats
----------------------------

### ![Redoc Logo](docs/img/redoc-logo-small.png)
View the GIGALOGISTICS API definition [online in your browser](https://heyoushan66.github.io/onepiece/). This web page is generated from the [OpenAPI definition](https://heyoushan66.github.io/onepiece) using [ReDoc](https://github.com/Redocly/redoc).


### ![Postman Logo](docs/img/postman-logo-small.png) Postman
The official [Postman reference collection](https://documenter.getpostman.com/view/305204/SW7W5V6o) for GIGALOGISTICS.  Just import it into [Postman](https://getpostman.com) and immediately begin interacting with the GIGALOGISTICS API. 