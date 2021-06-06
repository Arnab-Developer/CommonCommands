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
  --sku {B1, B2, B3, D1, F1, FREE, I1, I1v2, I2, I2v2, I3, I3v2, P1V2, P1V3, P2V2, P2V3, P3V2, P3V3, PC2, PC3, PC4, S1, S2, S3, SHARED} \
  --is-linux
```

Create a new app service

```
az webapp create 
  --name [] \
  --plan [] \
  --resource-group []
```