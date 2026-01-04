terraform init



**Azure**

az login && \
az account show && \
terraform plan && \
terraform apply


**GCP**


gcloud auth application-default login && \
gcloud config set project my-project-id && \
terraform plan && \
terraform apply


