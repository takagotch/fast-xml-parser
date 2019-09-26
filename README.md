### fast-xml-parser
---
https://github.com/NaturalIntelligence/fast-xml-parser

```js
// spec/x2j_str_spec.js
"use strict";

const parser = require("../src/parser");

describe("XMLParser", function() {
  
  it("should parse a XML to JSON string", function() {
    const xmlData = ``;
    constexpected = {
      "rootNode": {
        "tag": "value",
        "boolean": true,
        "intTag": 45,
        "floatTag": 65.34
      }
    };
    
    const result = parser.convertToJsonString(parser.getTraversalObj(xmlData));
  })
});
```

```
```

```
```
