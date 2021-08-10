---
uid: crmscript_ref_NSSentiment_SetConfidence
title: SetConfidence(Integer confidence)
intellisense: NSSentiment.SetConfidence
keywords: NSSentiment, GetConfidence
so.topic: reference
---

# SetConfidence(Integer confidence)

Sentiment analysis confidence, where available. 0 = no idea, 100 = perfectly confident, -1 = no confidence score available

**Parameter:** 
 - **confidence** Integer

```crmscript
NSSentiment thing;
Integer confidence;
thing.SetConfidence(confidence);
```

