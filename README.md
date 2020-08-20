# ACI with TLS Reverse Proxy and Sidecar ApplicationServer

## Change YAML settings
Optional: Change dnsNameLabel and fqdn.

## Create the Container Group
Create the Resourcegroup in the same region
```
export GROUP=myResourceGroup
az group create --name $GROUP --location northeurope
az container create --resource-group $GROUP --file container_group.yaml
```
