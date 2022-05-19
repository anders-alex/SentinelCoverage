# Azure Workbook - Microsoft Sentinel Coverage (Preview)
This Azure Workbook pulls the current Azure inventory via Azure Resource Graph explorer and compares it with data written to one or more selected Log Analytics workspaces to determine which resources are sending data and which ones are not. This can be used to expose gaps in your logging coverage and/or identify inactive resources.

## Considerations
- Current resources supported
  - Azure Virtual Machines
  - Azure Arc Servers
  - Azure PaaS Services (Subset, workbook will list supported resource types)
  - Azure Activity Logs
  - Azure AD Logs
  - Log Analytics Query Audit Logs

## Installation Instructions
1. Create a new Azure Workbook via the Azure Portal.
2. Open the Advanced Editor using the </> button on the toolbar.
3. Ensure you are on the Gallery Template tab.
4. Copy and paste the JSON text from the SentinelCoverage.workbook file.
5. Save the workbook.
