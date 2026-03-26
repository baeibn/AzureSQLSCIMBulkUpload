[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbaeibn%2FAzureSQLSCIMBulkUpload%2Fmain%2FAzureSQLSCIMBulkUpload-template.json)

# AzureSQLSCIMBulkUpload

Simple Azure Logic Apps workflow that converts a AzureSQL table/view to a SCIM bulk upload request that can be sent to the Entra ID provisioning service [/bulkUpload](https://learn.microsoft.com/graph/api/synchronization-synchronizationjob-post-bulkupload) API endpoint.

## How to use the Logic Apps workflow

Refer to the instructions [Quickstart API-driven inbound provisioning with Azure Logic Apps](https://aka.ms/Entra/InboundProvWithLogicApps).

For help and questions about Entra ID API-driven inbound provisioning, refer to the [documentation](https://aka.ms/Entra/ProvisionFromAnySource)
