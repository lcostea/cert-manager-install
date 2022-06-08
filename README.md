# cert-manager-install

Installation



```sh
kubectl apply -f namespace.yaml

NAMESPACE=cert-manager
SERVICE_NAME=cert-manager

helm dep update chart

helm upgrade --install $SERVICE_NAME chart/ --namespace $NAMESPACE --debug --atomic

```


