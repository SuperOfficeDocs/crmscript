---
uid: crmscript_ref_XMLNode_getName
title: XMLNode.getName()
intellisense: XMLNode.getName
keywords: getName()
so.topic: reference
so.yml: 1
---

# XMLNode.getName()

Gets the name of the XML tag.

## Example

```crmscript
XMLNode xml = XMLNode("root");
xml.setName("Root");
xml.setParameter("type", "object");

print(xml.getName());

//Prints "Root".
```
