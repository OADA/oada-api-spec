# File Formats

JSON schema that represents a list of precision ag file formats. 

### Schema
```json
{
  "title": "OADA Data File Format Schema",
  "description": "Array of precision ag data file formats that are supported by the provider.", 
  "type": "array",
    "items" : {
          "type" : "object",
          "properties" : {
               "short_name": {
                   "description": "Short abbreviated name of the data file format.",
                   "type": "string"
                },        
                "long_name": {
                   "description": "Long description of the data file format.", 
                   "type": "string"
                },
                   "description": {
                   "description": "Any additional information about the data file format.", 
                   "type": "string"
                }
            },
            "required":["short_name", "long_name"]
        }
}
```

### Example
```json
[
    {"short_name":"csv", "long_name":"Comma Separated Values"},
    {"short_name":"jd-gs-2", "long_name":"John Deere GreenStar 2"},
    {"short_name":"jd-gs-3", "long_name":"John Deere GreenStar 3"},
    {"short_name":"pp-2020-ss", "long_name":"Precision Planting 20/20 SeedSense"},
    {"short_name":"shp", "long_name":"Shape"},
    {"short_name":"tsv", "long_name":"Tab Separated Values"}
]
```
