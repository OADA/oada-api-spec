OADA API Specification
======================
The OADA API is intended to serve as a specification for all providers that desire to be OADA compliant. This API does not attempt to define or enforce a single industry data standard. The goal of this API is to enable interoperability between the many precision ag software systems and existing industry data types. By providing an extensible API that focuses on information exchange and facilitates data transformations an open heterogeneous environment that supports many legacy, current, and future data formats can be embraced.

License
--------
OADA is openly developed and built under the MIT License. 

Current Version
---------------
The current version of the OADA API specification is intended to be a draft revision to seek input and feedback from the larger precision ag community.

The draft specification has been defined in the RESTful API Modeling Language ([RAML](http://raml.org/)). The API specification in its entirety can be found here: [oada-api.raml](oada-api.raml)

Authentication
--------------
The open authorization standard OAuth 2 will be leveraged as the protocol to secure OADA APIs.

/files
------
Operations to add, update, and delete precision ag files from the growers datastore.
    
/metadata
---------
Operations to read and write metadata associated with precision ag files in the growers datastore. System defined metadata cannot be modified.
    
/search
-------
Returns metadata for all files that match the search criteria. Searches are limited to the folder path and its sub-folder hierarchy provided in the call.
    
/support/file_formats
---------------------
Returns a list of OEM or precision ag software system file formats recognized by this provider.

/support/transforms
-------------------
Returns if a desired transforms between file formats is supported by ths provider. 
      
/support/list
-------------
Returns a list of OEM or precision ag software system file formats recognized by this provider.

TODO
--------------
* Review terms and naming conventions in API and JSON schemas
* Validate syntax of API and JSON schemas
* Define list of precision ag data types: examples/data-types.json
* Define list of precision ag file formats: examples/supported-file-formats.json
* Verification suite
* Reference implementation
* Document sample curl requests

Help us make it better
----------------------
Please tell us how we can make the API better. If you have a specific feature request or if you found a bug, please use GitHub issues. Fork these docs and send a pull request with improvements. 
