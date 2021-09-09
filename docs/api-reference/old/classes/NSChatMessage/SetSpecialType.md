---
uid: crmscript_ref_NSChatMessage_SetSpecialType
title: SetSpecialType(NSChatMessageSpecialType specialType)
intellisense: NSChatMessage.SetSpecialType
keywords: NSChatMessage, GetSpecialType
so.topic: reference
---

# SetSpecialType(NSChatMessageSpecialType specialType)

Enum indicating if it is a special message, such as an URL redirection, etc.

## Parameters

* **specialType** NSChatMessageSpecialType

### Enum: specialType

* 0 = None
* 1 = Welcome
* 2 = Url
* 3 = Block
* 5 = NewSession
* 6 = TransferedSession
* 7 = Error
* 8 = SessionDeleted
* 9 = FaqSuccessQuestion
* 10 = ClosedByUser
* 11 = ClosedByCustomer
* 12 = ClosedByIdle
* 13 = TransferRejected
* 14 = ReopenedByCustomer
* 15 = ClickedOption
* 16 = BotMessage
* 17 = Options

## Example

```crmscript
NSChatMessage thing;
NSChatMessageSpecialType specialType;
thing.SetSpecialType(specialType);
```
