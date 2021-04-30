﻿---
uid: crmscript_ref_NSDocumentAgent_SetDocumentStreamFromId
title: DocumentEntity SetDocumentStreamFromId(Integer documentId, Stream stream)
intellisense: NSDocumentAgent.SetDocumentStreamFromId
keywords: NSDocumentAgent, SetDocumentStreamFromId
so.topic: reference
---

Store document content from stream. Since there is a potential for a name conflict (the file name stored by the document entity earlier may prove to be invalid), the (possibly amended) document entity is returned. The client should not assume that any earlier, cached entity information is valid.

**Parameters:**
 - **documentId** The document entity object that the binary data (document) should be stored to. Its file name may be amended by this call, see the return value.
 - **stream** The document content as a stream.

**Returns:** Since there is a potential for a name conflict (the file name stored by the document entity earlier may prove to be invalid), the (possibly amended) document entity is returned. The client should not assume that any earlier, cached entity information is valid.

```crmscript
NSDocumentAgent agent;
Integer documentId;
Stream stream;
DocumentEntity res = agent.SetDocumentStreamFromId(documentId, stream);
```
