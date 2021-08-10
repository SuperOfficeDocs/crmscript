---
uid: crmscript_ref_NSTemporaryKeyInfo_SetDomain
title: SetDomain(Integer domain)
intellisense: NSTemporaryKeyInfo.SetDomain
keywords: NSTemporaryKeyInfo, GetDomain
so.topic: reference
---

# SetDomain(Integer domain)

The domain for this key. Unknown if key is not valid.

**Parameter:** 
 - **domain** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = MailingRecipient 
     - Enum: 2 = FormSubmitterRecipient 
     - Enum: 3 = ViewTicketInCustomerCenter 
     - Enum: 4 = LoginCustomerCenter 
     - Enum: 5 = PublicFaq 
     - Enum: 6 = ChangePasswordCustomerCenter 

```crmscript
NSTemporaryKeyInfo thing;
Integer domain;
thing.SetDomain(domain);
```

