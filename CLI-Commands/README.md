## *Basic Azuer CLI Commands for AZ-204 Exam*

#### Login to azure account 
```
az login 
```
#### Get help
```
 az account -h
```

#### Get all  resource groups
```
az group list --output table
```

#### Create a resource group
```
az group create --name AZT200 --location centralindia
```

#### Create a windows VM
```
az vm create --resource-group AZT200 --name AZTvm --image win2019datacenter --admin-username AZT
```
