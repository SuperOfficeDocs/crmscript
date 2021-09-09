---
uid: crmscript_ref_String
title: String
intellisense: Void.String
so.topic: reference
so.yml: 1
---

# String

A class for representing strings as objects.
Constructor can take a string and returns a string.

## Example

```crmscript
String s = "47882255";

if (s.isDigit() && s.getLength() == 8){
  print(s + " is a valid phone number");
}
```
