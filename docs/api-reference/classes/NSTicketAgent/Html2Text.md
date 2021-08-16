---
uid: crmscript_ref_NSTicketAgent_Html2Text
title: String Html2Text(String content)
intellisense: NSTicketAgent.Html2Text
keywords: NSTicketAgent, Html2Text
so.topic: reference
---

# String Html2Text(String content)

Create a plain text version of the html, suitable for email

**Parameters:**
 - **content** The html version

**Returns:** The plain text version

```crmscript
NSTicketAgent agent;
String content;
String res = agent.Html2Text(content);
```

