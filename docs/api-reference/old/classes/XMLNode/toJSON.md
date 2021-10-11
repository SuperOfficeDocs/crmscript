---
uid: crmscript_ref_XMLNode_toJSON_Integer_indent
title: XMLNode.toJSON(Integer indent)
intellisense: XMLNode.toJSON
keywords: toJSON(Integer)
so.topic: reference
so.yml: 1
---

# XMLNode.toJSON(Integer indent)

Creates a string containing XML nodes formatted as a JSON document. Child nodes are also included.

## Parameters

* **Indent:** the text with a given number of spaces.
* **Returns:** XMLNodes converted to JSON

The XMLNode parameter "type" is used to describe the datatype of the JSON nodes.

Legal types: object, array, string, number, bool, and null.

## Example

```crmscript
XMLNode xml = XMLNode("root");
xMenu.setParameter("type", "object");

XMLNode xMenu = XMLNode("menu");
xMenu.setParameter("type", "string");
xMenu.setText("truls");
xml.addChild(xMenu);

XMLNode xFoo = XMLNode("foo");
xFoo.setParameter("type", "number");
xFoo.setText("1.23456");
xml.addChild(xFoo);

print(xml.toString(0));
```

**Output:**

```json
{
  "menu": "truls",
  "foo": 1.23456
}
```