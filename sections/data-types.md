# Data Types

JSON schema that represents a list of precision ag farming operations or tasks. Data types are used to represent that type of data in precision ag files.

### Schema
```json
{
  "title": "OADA Data Types Schema",
  "description": "Precision ag data types.", 
  "type": "array",
    "items" : {
          "type" : "object",
          "properties" : {
               "short_name": {
                   "description": "",
                   "type": "string"
                },        
                "long_name": {
                   "description": "", 
                   "type": "string"
                },
                   "description": {
                   "description": "", 
                   "type": "string"
                }
            },
            "required": ["short_name", "long_name"]
        }       
}
```

### Example
```json
[
    {"short_name":"asap", "long_name":"As-Applied"},
    {"short_name":"hvst", "long_name":"Harvest"},
    {"short_name":"ppre", "long_name":"Planting Prescription"},
    {"short_name":"ss", "long_name":"Soil Samples"},
    {"short_name":"yld", "long_name":"Yield"}
]
```
