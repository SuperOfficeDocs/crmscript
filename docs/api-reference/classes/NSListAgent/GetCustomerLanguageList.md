---
uid: crmscript_ref_NSListAgent_GetCustomerLanguageList
title: NSCustomerLanguage[] GetCustomerLanguageList(Integer[]  customerLanguageIds);
intellisense: NSListAgent.GetCustomerLanguageList
keywords: NSListAgent, GetCustomerLanguageList
so.topic: reference
---

Gets a vector of NSCustomerLanguage objects.

**Parameters:**
 - **customerLanguageIds** The identifiers of the NSCustomerLanguage objects

**Returns:** Vector of NSCustomerLanguage objects

```crmscript
Integer[] ids;
NSListAgent agent;
agent.GetCustomerLanguageList(ids);
```

