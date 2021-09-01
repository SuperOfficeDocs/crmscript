---
title: XMLNode parseJSON2(String jsonDocument)
description: XMLNode parseJSON2(String jsonDocument)
intellisense: Void.parseJSON2
langref: 1
keywords: parseJSON2(String)
so.topic: reference
---

# XMLNode parseJSON2(String jsonDocument)

Parse a JSON document and generate a tree of XMLNode's.

## Example

```crmscript
String jsonString = "{"menu": {"liste": [ "1", "2", "3", true, 123, 1.23 ],"id": "file","value": "File","tall": 1.234567,"sant": true,"usant": false,"tom": null,"popup": {"menuitem": [{"value": "New", "onclick": "CreateNewDoc()"},{"value": "Open", "onclick": "OpenDoc()"},{"value": "Close", "onclick": "CloseDoc()"}]}}}";

XMLNode xmlObject = parseJSON2(jsonString); // Converts jsonString to XML
printLine(xmlObject.toJSON(0)); // Prints out the actual JSON content
```

See example JSON and output XML in parseJSON().
