---
uid: crmscript_ref_NSDocumentAgent_SubstituteTemplateVariablesWithCustomTags
title: String SubstituteTemplateVariablesWithCustomTags(String source, Integer generatorEncoding, String[] customTags, String[] customValues, Integer contactId, Integer personId, Integer appointmentId, Integer documentId, Integer saleId, Integer selectionId, Integer projectId, String cultureName)
intellisense: NSDocumentAgent.SubstituteTemplateVariablesWithCustomTags
keywords: NSDocumentAgent, SubstituteTemplateVariablesWithCustomTags
so.topic: reference
---

# String SubstituteTemplateVariablesWithCustomTags(String source, Integer generatorEncoding, String[] customTags, String[] customValues, Integer contactId, Integer personId, Integer appointmentId, Integer documentId, Integer saleId, Integer selectionId, Integer projectId, String cultureName)

Parse the source string, and replace any template variable tags with their values, based on the ID's given in the other parameters.<p/>This method also takes a pair of arrays specifying custom tags and their values; these tags will be available during substitution in addition to all the existing tags. Custom values will override values otherwise set.

## Parameters

* **source** Source string to parse for template variables. Such variables must have delimiters corresponding to the standard for the given generator encoding. Non-text source data (such as the binary content of a .doc file) should be passed in as Base64.
* **generatorEncoding** Encoding of source string. Non-text formats such as MsWord or Excel should be Base64 encoded in the source string.
* **customTags** Array of custom tag names. Each name should have exactly four characters. There should be exactly one value for each tag, i.e., the lengths of the customTags and customValues arrays should be the same.
* **customValues** Array of values for custom tags. There should be exactly one value for each tag, i.e., the lengths of the customTags and customValues arrays should be the same.
* **contactId** Identifier for a contact
* **personId** Identifier for a person
* **appointmentId** Identifier for an appointment
* **documentId** Identifier for a document
* **saleId** Identifier for a sale
* **selectionId** Identifier for a selection
* **projectId** Identifier for a project
* **cultureName** Name of culture to be used for culture-sensitive data, such as dates or multi-language texts. Use a blank string to accept whatever current culture is set on the server (possibly not a good choice in multinational organizations with a single server).

**Returns:** String

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
NSDocumentAgent agent;
String source;
Integer generatorEncoding;
String[] customTags;
String[] customValues;
Integer contactId;
Integer personId;
Integer appointmentId;
Integer documentId;
Integer saleId;
Integer selectionId;
Integer projectId;
String cultureName;
String res = agent.SubstituteTemplateVariablesWithCustomTags(source, generatorEncoding, customTags, customValues, contactId, personId, appointmentId, documentId, saleId, selectionId, projectId, cultureName);
```
