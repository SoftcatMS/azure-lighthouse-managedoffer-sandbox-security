# Azure Lighthouse Managed Offer (sandbox)
Stores the Azure Lighthouse Managed Security Offer template that can be used to provide delegation to customer environments from objects with the Partner Sandbox account

The following permissions are included in this lighthouse offer.

# Delegated Permissions

| User/Group | Delegated Permission |
| ---------- | -------------------- |
| Managed Azure - SIEM Contributors | Microsoft Sentinel Contributor |
| Managed Azure - SIEM Contributors | Log Analytics Reader |

# Deploy to Azure 

Use the below button to deploy this Azure Lighthouse offer to a tenant.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSoftcatMS%2Fazure-lighthouse-managedoffer-sandbox-security%2Fmain%2Fsandbox-security-lighthouse-offer-nopim.json)
