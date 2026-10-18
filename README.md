# IOI M365 & Power Platform Migration Suite

[![Power Platform](https://img.shields.io/badge/Power%20Platform-ALM%20Suite-742774?style=for-the-badge&logo=powerplatform&logoColor=white)](https://powerplatform.microsoft.com)
[![PowerShell](https://img.shields.io/badge/PowerShell-Automation-5391FE?style=for-the-badge&logo=powershell&logoColor=white)](https://learn.microsoft.com/powershell/)
[![Microsoft 365](https://img.shields.io/badge/M365-Enterprise%20Migration-D83B01?style=for-the-badge&logo=microsoft&logoColor=white)](https://microsoft365.com)

**IOI M365 Migration Suite** is the operational deployment, schema provisioning, and PowerShell automation toolkit supporting the full migration lifecycle of IOI Acidchem's enterprise systems into Microsoft 365 and Dataverse.

---

## 🌟 Suite Capabilities

- **Automated SharePoint List Provisioning**: PnP PowerShell scripts that generate enterprise SharePoint lists with correct column types, lookup constraints, and index settings.
- **Dataverse Solution Packaging**: Declarative solution unpacker and packer for Power Platform ALM and continuous delivery.
- **Data Verification & Audit Scripts**: Validates historical data records migrated from Domino against target Dataverse tables to guarantee 100% data integrity.

---

## 🚀 Deployment Instructions

```powershell
# Connect to SharePoint Online tenant
Connect-PnPOnline -Url "https://ioigroup.sharepoint.com/sites/acidchem" -Interactive

# Execute automated list and permission provisioning
.\scripts\Deploy-M365Schema.ps1 -Environment Production
```

---

## 📄 License
Proprietary solution maintained by **Ali Akhmad Fauzie** ([@aliakhmadfauzie](https://github.com/aliakhmadfauzie)).
