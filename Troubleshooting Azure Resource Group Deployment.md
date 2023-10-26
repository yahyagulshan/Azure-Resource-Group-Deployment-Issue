# Troubleshooting Azure Resource Group Deployment


<strong style="color: red; opacity: 0.80;">Issue:</strong> The process becomes stuck during the database step when deploying resources to an Azure resource group. An error message is displayed

 <strong style="color: red; opacity: 0.80;">Error Message::</strong>
<span style='color: red;'>"Operation on server 'abcdef-database' and database 'abcdef-database' is in progress. Please wait a few minutes before trying again."</span>

<strong style="color: red; opacity: 0.80;">Resolution:</strong>
Immediate Action: Retry the deployment after waiting for a couple of minutes. The error message may be due to a temporary server operation or database update.
Check for Azure Maintenance: It's possible that Azure is performing maintenance, patching, or updates in the background. 
These activities can temporarily affect deployment processes. Waiting for a while can often resolve the issue.


