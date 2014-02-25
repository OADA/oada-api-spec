# Metadata
Operations to read and write metadata associated with precision ag files in the growers datastore. System defined metadata cannot be modified.

## Put
Uploads a metadata file using PUT semantics. The preferred HTTP method for this call is PUT. For compatibility with browser environments, the POST HTTP method is also recognized. Note: Providing a Content-Length header set to the size of the uploaded file is required so that the server can verify that it has received the entire file contents.

## Get
The specified file's metadata at the requested revision. 
