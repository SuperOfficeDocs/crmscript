---
uid: crmscript_ref_XMLNode_getParameter_String_name
title: XMLNode.getParameter(String name)
intellisense: XMLNode.getParameter
keywords: getParameter(String)
so.topic: reference
so.yml: 1
---

# XMLNode.getParameter(String name)

Gets a parameter (attribute) from the node with a given name.

## Parameters

* **name:** the key to get the value of.

## Example

```crmscript
XMLNode xml = XMLNode("root");
xml.setName("Root");
xml.setParameter("type", "object");

print(xml.getParameter("type"));

Prints "object".
```
