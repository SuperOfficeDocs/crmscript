---
uid: crmscript_ref_ReplyTemplate
title: ReplyTemplate
intellisense: Void.ReplyTemplate
so.topic: reference
---

# ReplyTemplate

This class represents a reply template.

## Example

    ReplyTemplate rt;
    
    rt.load(2); // Loads a reply template with id = 2
    
    Parser p;
    
    String parsedString = p.parseString(rt.getBody(0)); // Parses the body of the template through a parser object
