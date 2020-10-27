Download a GitHub Repository
============================

            

This runbook copies a GitHub repository to the local sandbox running the runbook, similar to what 'git pull' would do, and returns the path to the repository.



Requires a GitHub access token, stored in an encrypted Automation variable asset. See
[https://help.github.com/articles/creating-an-access-token-for-command-line-use](https://help.github.com/articles/creating-an-access-token-for-command-line-use) for how to generate a token for your Github account.


When using this runbook, be aware that the memory and disk space size of the processes running your runbooks is limited. Because of this, we recommened using runbooks only to transfer small repositories. All Automation Integration
 Module assets in your account are loaded into your processes, so be aware that the more Integration Modules you have in your system, the smaller the free space your processes will have. To ensure maximum disk space in your processes, make sure to clean up
 any local files a runbook transfers or creates before the runbook completes.


 

 
 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
