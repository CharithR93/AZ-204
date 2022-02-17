## *Basic Azuer CLI Commands for AZ-204 Exam*


Description | Command 
--- | --- 
*Login to azuer account * | az login 
* Get help for to complete commands * | az account -h
*Get all  resource groups* | az group list --output table
*Create a resource group* |az group create --name AZT200 --location centralindia
*Create VM* |az vm create --resource-group AZT200 --name AZTvm --image win2019datacenter --admin-username AZT