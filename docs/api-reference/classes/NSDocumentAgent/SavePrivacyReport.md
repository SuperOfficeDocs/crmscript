﻿---
uid: crmscript_ref_NSDocumentAgent_SavePrivacyReport
title: Integer SavePrivacyReport(String htmlReport, String title, Integer personId)
intellisense: NSDocumentAgent.SavePrivacyReport
keywords: NSDocumentAgent, SavePrivacyReport
so.topic: reference
---

Generates a Pdf from HTML and makes a document

**Parameters:**
 - **htmlReport** Html to convert
 - **title** Title of report
 - **personId** Person id associated with the report

**Returns:** Integer

```crmscript
NSDocumentAgent agent;
String htmlReport;
String title;
Integer personId;
Integer res = agent.SavePrivacyReport(htmlReport, title, personId);
```

