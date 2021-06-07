# Web app (CLI)

Create a new resource group

```
az group create --name [resource-group-name] --location [azure-location]
```

Create a new app service plan

```
az appservice plan create 
  --name [] \
  --resource-group [] \
  --location [] \
  --sku FREE
```

Create a new app service

```
az webapp create 
  --name [] \
  --plan [] \
  --resource-group [] \
  --runtime []
```