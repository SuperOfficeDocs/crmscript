﻿---
uid: crmscript_ref_NSEMailAgent_SaveEmailToTmpDocument
title: String SaveEmailToTmpDocument(NSEMailEntity email, Integer folderId, Bool stripAttachments)
intellisense: NSEMailAgent.SaveEmailToTmpDocument
keywords: NSEMailAgent, SaveEmailToTmpDocument
so.topic: reference
---

Save the Email as a tmp document ready to archive

**Parameters:**
 - **email** The e-mail to save
 - **folderId** The folder id where the email is
 - **stripAttachments** If true, do not include attachments in tmp document

**Returns:** Filename of the tmp document

```crmscript
NSEMailAgent agent;
NSEMailEntity email;
Integer folderId;
Bool stripAttachments;
String res = agent.SaveEmailToTmpDocument(email, folderId, stripAttachments);
```

