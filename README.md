# microservices
For docker on google cloud
  docker-machine create --driver google --google-project docker-271309 --google-zone europe-west1-b --google-machine-type f1-micro --google-machine-image $(gcloud compute images list --filter ubuntu-1604-lts --uri) docker-host
  gcloud compute instances stop docker-host --zone=europe-west1-b
