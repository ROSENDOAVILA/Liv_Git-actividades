# Comandos de gcloud

- Listar Compute Engine : 
```
 gcloud compute instances list
 ```

- Listar IPs en uso, existentes o reservadas: 
```
 gcloud compute instances list
 ```
 - Listar buckets disponibles:
```
 gcloud storage ls
 ```
  - Listar Service Accounts existentes en un proyecto:
```
 gcloud iam service-accounts list
```

## Comandos adicionales 

- Consulta información sobre tu proyecto de Compute Engine
```
 gcloud compute project-info describe
```
- Muestra todos los datos asociados a una VM
```
 gcloud compute instances describe VM_NAME
```

## Bibliografia

* https://cloud.google.com/compute/docs/gcloud-compute/common-commands?hl=es-419

* https://cloud.google.com/compute/docs/instances/view-ip-address?hl=es-419#gcloud

* https://cloud.google.com/storage/docs/listing-buckets?hl=es-419#cli-list-buckets

* https://cloud.google.com/sdk/gcloud/reference/iam/service-accounts/list