Set-WebAppServicePlan - Change app service plan of a web app in Azure
=====================================================================

            

This function can change the app service plan of a website in Azure. It can also turn on AutoScale.

It is not really production ready (should have more checks and error handling) but was created to give someone an idea on how to work with the new Azure module. So it's a bit simple by design :-)


 


It uses the fairly new (at the time I'm writing this at least) Azure preview module, see this link:
[https://azure.microsoft.com/en-us/blog/azps-1-0-pre/](https://azure.microsoft.com/en-us/blog/azps-1-0-pre/)


 


A few examples of usage:




This will set the app service plan to 'Standard' and enable Autoscale.




 




It will scale the web app from 'Free' to 'Standard' with Autoscale turned on (CPU metrics), and then back to free when the alert is resolved.






I hope it can be of use for someone!







        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
