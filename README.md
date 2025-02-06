# API

### Build

```bash
docker build . -t api:test
```

kubectl create secret docker-registry regcred --docker-server=habor.analytichpxv3.online --docker-username=jacknokhook --docker-password=J@ckza39 --docker-email=jacknokhook@gmail.com

Forward Port
kubectl port-forward svc/nginx 8080:8080

helm install app-uat . -f ./values/uat.yaml -n app-uat
helm upgrade app-uat . -f ./values/uat.yaml -n app-uat
helm uninstall app-uat app-uat -n app-uat
