---
uid: crmscript_ref_Message
title: Message
intellisense: Void.Message
sortOrder: 539
so.topic: reference
---

# Message

Class for representing an eJournal ticket message.

## Example

    Message m;
    
    m.load(2); // Loads message with id = 2
    m.setValue("emailHeader", "Test");
    m.setValue("body", "This is a test");
    m.save();
    m.send("bob@example.com", "simon@example.com", Null, "Test"); // To, cc, bcc, subject
