---
uid: crmscript_ref_NSQuoteConnection_GetDisplayName
title: String GetDisplayName()
intellisense: NSQuoteConnection.GetDisplayName
keywords: NSQuoteConnection, GetDisplayName
so.topic: reference
---

# String GetDisplayName()

Connection name shown to user; multi-language support. The name of the connector to display in a list so that the users can choose between them. Typically the name of the client, with maybe the ERP system in parenthesis.

**Returns:** String

```crmscript
NSQuoteConnection thing;
String displayName  = thing.GetDisplayName();
```

