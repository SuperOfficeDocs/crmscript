---
uid: crmscript_ref_NSSaleTypeEntity_SetConfirmationLinesTemplate
title: SetConfirmationLinesTemplate(Integer confirmationLinesTemplate)
intellisense: NSSaleTypeEntity.SetConfirmationLinesTemplate
keywords: NSSaleTypeEntity, GetConfirmationLinesTemplate
so.topic: reference
---

# SetConfirmationLinesTemplate(Integer confirmationLinesTemplate)

The template that this sale type should use when producing the order confirmation lines document; the template must have DocTmplQuoteType=ConfirmationLines

**Parameter:** 
 - **confirmationLinesTemplate** Integer

```crmscript
NSSaleTypeEntity thing;
Integer confirmationLinesTemplate;
thing.SetConfirmationLinesTemplate(confirmationLinesTemplate);
```

