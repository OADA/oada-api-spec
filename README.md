OADA API Specification
======================
The OADA API is intended to serve as a specification for all providers that desire to be OADA compliant. This API does not attempt to define or enforce a single industry data standard. The goal of this API is to enable interoperability between the many precision ag software systems and existing industry data types. By providing an extensible API that focuses on information exchange and facilitates data transformations an open heterogeneous environment that supports many legacy, current, and future data formats can be embraced.

## License
OADA is openly developed and built under the MIT License. 

## Current Version
The current version of the OADA API specification is intended to be a draft revision to seek input and feedback from the larger precision ag community.

The draft specification has been defined in the RESTful API Modeling Language ([RAML](http://raml.org/)). The draft API specification in its entirety can be found here: [oada-api.raml](oada-api.raml)

The draft specification can also be viewed with RAML api-console project developed by [mulesoft/api-console](https://github.com/mulesoft/api-console). A OADA specific version that reads directly from the OADA github repository can be found at the following links:

- [Active Development draft](http://openag.io/api-console/?raml=https://api.github.com/repos/OADA/oada-api-spec/contents/oada-api.raml?ref=raml/v0_2)

## Wrappers and example code
 * [Sinatra OADA API Impl](https://github.com/OADA/oada-api-sinatra-impl)

## Authentication
OADA APIs use the open authorization protocol [OAuth 2.0](http://oauth.net/2/) to secure access to grower data.

## API Endpoints
 * [Files](sections/files.md)
 * [Metadata](sections/metadata.md)
 * [Search](sections/search.md)
 * [Support](sections/support.md)

## Schemas
 * [Data Types](sections/data-types.md)
 * [File Formats](sections/file-formats.md)
 * [File Metadata](sections/file-metadata.md)
 
## Verification Suite
TODO

## Help us make it better
Please tell us how we can make the API better. If you have a specific feature request or if you found a bug, please use GitHub issues. Fork these docs and send a pull request with improvements. Join the [oada-dev](https://groups.google.com/forum/?hl=en#!forum/oada-dev) mailing list.
