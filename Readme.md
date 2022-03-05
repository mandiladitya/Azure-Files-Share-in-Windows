### Mount Azure File Share In Windows

```
kubectl create secret generic azure-secret \
--from-literal=azurestorageaccountname=$AKS_PERS_STORAGE_ACCOUNT_NAME \
--from-literal=azurestorageaccountkey=$STORAGE_KEY
```
