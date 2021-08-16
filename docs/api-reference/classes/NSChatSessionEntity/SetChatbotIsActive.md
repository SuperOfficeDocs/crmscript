---
uid: crmscript_ref_NSChatSessionEntity_SetChatbotIsActive
title: SetChatbotIsActive(Bool chatbotIsActive)
intellisense: NSChatSessionEntity.SetChatbotIsActive
keywords: NSChatSessionEntity, GetChatbotIsActive
so.topic: reference
---

# SetChatbotIsActive(Bool chatbotIsActive)

Indicates that a chatbot is active on the session. This will cause bot triggers to fire. Set to 0 when bot hands off to user.

**Parameter:** 
 - **chatbotIsActive** Bool

```crmscript
NSChatSessionEntity thing;
Bool chatbotIsActive;
thing.SetChatbotIsActive(chatbotIsActive);
```

