```
 - Listar Compute Engine : gcloud compute instances list https://cloud.google.com/compute/docs/gcloud-compute/common-commands?hl=es-419
 ```
  gcloud compute project-info describe

```
 - Listar IPs en uso, existentes o reservadas: gcloud compute instances list  https://cloud.google.com/compute/docs/instances/view-ip-address?hl=es-419#gcloud

 gcloud compute instances describe instance-name \
  --format='get(networkInterfaces[0].networkIP)'



 - Listar buckets disponibles: gcloud storage ls	https://cloud.google.com/storage/docs/listing-buckets?hl=es-419#cli-list-buckets
 ```
```
 - Listar Service Accounts existentes en un proyecto: gcloud iam service-accounts list	https://cloud.google.com/sdk/gcloud/reference/iam/service-accounts/list
```
