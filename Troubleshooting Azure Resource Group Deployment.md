# Troubleshooting Azure Resource Group Deployment



<strong style="color: red; opacity: 0.80;">**Issue**:</strong> The process becomes stuck during the database step when deploying resources to an Azure resource group. An error message is displayed

 <strong style="color: red; opacity: 0.80;">Error Message:</strong> 
 <!-- ```diff

``` -->
$${\color{red}"Operation \space on \space server \space 'abcdef-database' \space and \space database  \space 'abcdef-database' \space  is \space  in \space progress. \space Please \space wait \space a \space few \space minutes \space before \space trying \space again. " \space}$$


<!-- ${\color{red}**Resolution**}$ -->

<code style="color: #ff0000">This is red text.</code>

<strong>**Resolution**:</strong>


<strong style="color: red; opacity: 0.80;">**Immediate Action**:</strong> Retry the deployment after waiting for a couple of minutes. The error message may be due to a temporary server operation or database update.

<strong style="color: red; opacity: 0.80;">**Check for Azure Maintenance**:</strong> It's possible that Azure is performing maintenance, patching, or updates in the background. 
These activities can temporarily affect deployment processes. Waiting for a while can often resolve the issue.

<!-- $${\color{red}This text is red.}$$ -->

<!-- ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
``` -->