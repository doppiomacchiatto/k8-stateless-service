Create dictionary-deploymnet
```
kubectl create -f dictionary-deployment.yaml
```
Create dictionary-server-service
```
kubectl create -f dictionary-lb.yaml

Create Varnish config map
```
kubectl create configmap varnish-config --from-file=default.vcl
```