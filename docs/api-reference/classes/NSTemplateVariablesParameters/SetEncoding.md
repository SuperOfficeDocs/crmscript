---
uid: crmscript_ref_NSTemplateVariablesParameters_SetEncoding
title: SetEncoding(Integer encoding)
intellisense: NSTemplateVariablesParameters.SetEncoding
keywords: NSTemplateVariablesParameters, GetEncoding
so.topic: reference
---

# SetEncoding(Integer encoding)

Encoding of source string. Non-text formats such as MsWord or Excel should be Base64 encoded in the source string.

## Parameters

* **encoding** Integer

### Enum: generatorEncoding

* 0 = Text
* 1 = Html
* 2 = Xml
* 3 = MsWord
* 4 = MsExcel
* 5 = MsPowerpoint
* 6 = MsOffice2007
* 7 = MsOffice2007Xml
* 8 = Url
* 9 = UrlUnicode
* 10 = Pdf
* 11 = Mime
* 12 = OpenDocument
* 13 = OpenDocumentXml

## Example

```crmscript
NSTemplateVariablesParameters thing;
Integer encoding;
thing.SetEncoding(encoding);
```
