---
uid: crmscript_ref_NSTicketMessageEntity_SetMessageId
title: SetMessageId(String messageId)
intellisense: NSTicketMessageEntity.SetMessageId
keywords: NSTicketMessageEntity, GetMessageId
so.topic: reference
---

# SetMessageId(String messageId)

The X-Message-Id header value from the email. Used for threading, i.e. connecting messages to existing tickets.

**Parameter:** 
 - **messageId** String

```crmscript
NSTicketMessageEntity thing;
String messageId;
thing.SetMessageId(messageId);
```

