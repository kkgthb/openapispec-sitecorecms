Sitecore CMS doesn't provide OpenAPI/Swagger specification files for some of their most important REST APIs.

This repository contains some handwritten ones that do not reflect the full level of detail that _can_ be provided by these APIs.

However, they can be used to learn the most common request structure expectations of the most common API endpoints.

They also provide minimalist example responses that can be used to drive a mock server.

Endpoints documented:

1. Sitecore [XP Layout Service](https://doc.sitecore.com/xp/en/developers/hd/latest/sitecore-headless-development/layout-service.html) / [XM Cloud Layout Service](https://doc.sitecore.com/xmc/en/developers/xm-cloud/layout-service.html) ([see file in repo](layoutservice.yml), [see raw file](layoutservice.yml?raw=1), [see SwaggerUI](https://editor.swagger.io/?url=https://raw.githubusercontent.com/kkgthb/openapispec-sitecorecms/main/layoutservice.yml))
