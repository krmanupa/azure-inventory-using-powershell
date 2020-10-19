Azure Inventory using Powershell
================================

            
Want to know about innovative and interesting ideas in Azure and automation? Check out my blog: https://manjunathrao.com.




Version 2.0:
I have changed the design of this script. It no longer creates a single Excel sheet. Rather, produces a CSV file for individual services inside individual subscription's folder.

DESCRIPTION: This script will pull the infrastructure details of the Azure subscriptions. Details will be stored under the folder 'c:\AzureInventory'If you have multiple subscriptions, a separate folder will be created for individual subscription.CSV files
 will be created for individual services (Virtual Machines, NSG rules, Storage Account, Virtual Networks, Azure Load Balancers) inside the subscription's directory


 
 


        
    
Note: TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group.
