---
uid: crmscript_ref_Generic_getStructMembers_String_name
title: Generic.getStructMembers(String name)
intellisense: Generic.getStructMembers
langref: 1
sortOrder: 145
keywords: getStructMembers(String)
so.topic: reference
---

# Generic.getStructMembers(String name)

Get a list of the struct members (variables, not functions) of a struct given its name.

```crmscript
Building BuildingGeneric(String json){
  Building b;
  String[] fields = getStructMembers("Building");
  XMLNode root = parseJSON(json);
  for(Integer i = 0; i < fields.length(); i++) {
    Generic g = getGenericValue(b, fields[i]);
    String value = root.getValueFromPath(fields[i]);
    setGenericFromString(g, value);
  }
  
  return b;
}

* **value:** String Name of struct, for example "Person"
* **Returns:** String[] array of member names, for example ["name", "age", "dob"]
