# Files
Operations to add, update, and delete precision ag files from the growers datastore.

### Put
Uploads a file using PUT semantics. The preferred HTTP method for this call is PUT. For compatibility with browser environments, the POST HTTP method is also recognized. Note: Providing a Content-Length header set to the size of the uploaded file is required so that the server can verify that it has received the entire file contents.

### Get
Get the specified file's contents at the requested revision. The file can optionally return in an alternate format by setting the file_format query parameter. The HTTP response contains the content metadata in JSON format within an x-oada-file-metadata header.

### Delete
Deletes a file and its associated metadata.
