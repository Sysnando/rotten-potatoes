# rotten-potatoes

## Configuração

By default the mongo db config are already added. But in order to move to production you must update this variables in the k8s/deployment.yaml or create secret configs in your repo:
MONGODB_DB => database name |
MONGODB_HOST => MongoDB hobs
MONGODB_PORT => MongoDB access port
MONGODB_USERNAME => MongoDB user
MONGODB_PASSWORD => MongoDB password

## Config
Add the 3 secret configs below in you repo:
DOCKERHUB_USER = your docker hub user
DOCKERHUB_PWD = your docker hub password
K8S_KUBE_CONFIG = the k8s configuration "~/kube/config"
