---
uid: crmscript_ref_NSCheckLicenseStatusResult_GetLicenseStatus
title: Integer GetLicenseStatus()
intellisense: NSCheckLicenseStatusResult.GetLicenseStatus
keywords: NSCheckLicenseStatusResult, GetLicenseStatus
so.topic: reference
---

# Integer GetLicenseStatus()

Result of CheckLicenseStatus

**Returns:** Integer

## Enum: LicenseStatus

* 0 = Ok
* 1 = NewLicenseAvailable
* 2 = NewCompanyNameAvailable
* 3 = NewSerialAvailable
* 4 = UseCustomMessage
* 5 = UseCustomMessageAndUrl
* 100 = ProblemWithLicense
* 5000 = UnknownError

## Example

```crmscript
NSCheckLicenseStatusResult thing;
Integer licenseStatus  = thing.GetLicenseStatus();
```
