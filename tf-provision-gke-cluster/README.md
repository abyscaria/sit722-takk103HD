Updated by : Aby Scaria

This code will provision a GKE cluster in the Google cloud platform

Referemces: https://developer.hashicorp.com/terraform/tutorials/gcp-get-started/google-cloud-platform-build

updat the project details and the clusture name accoridn to the resouces in your google cloud platform

run following command to initate and provision the resouces 

$ gcloud auth login # to login to your cloud platform and to autheniticate to perform the build activities

$ terrrafom init # to initiate the configuration

$ terraform plan # to verify the configuration is correct and rectify the errors if any

$ terraform apply # to provision the infrastructure and perform the build 
