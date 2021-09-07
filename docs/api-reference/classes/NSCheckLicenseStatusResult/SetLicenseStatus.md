---
uid: crmscript_ref_NSCheckLicenseStatusResult_SetLicenseStatus
title: SetLicenseStatus(Integer licenseStatus)
intellisense: NSCheckLicenseStatusResult.SetLicenseStatus
keywords: NSCheckLicenseStatusResult, GetLicenseStatus
so.topic: reference
---

# SetLicenseStatus(Integer licenseStatus)

Result of CheckLicenseStatus

## Parameters

* **licenseStatus** Integer

### Enum: LicenseStatus

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
Integer licenseStatus;
thing.SetLicenseStatus(licenseStatus);
```
