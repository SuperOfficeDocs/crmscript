---
uid: crmscript_ref_NSChatMessage_GetSpecialType
title: NSChatMessageSpecialType GetSpecialType()
intellisense: NSChatMessage.GetSpecialType
keywords: NSChatMessage, GetSpecialType
so.topic: reference
---

# NSChatMessageSpecialType GetSpecialType()

Enum indicating if it is a special message, such as an URL redirection, etc.

**Returns:** NSChatMessageSpecialType

## Enum: specialType

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
NSChatMessageSpecialType specialType  = thing.GetSpecialType();
```
