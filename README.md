# API

### Build

```bash
docker build . -t api:test
```



helm install app-uat . -f ./values/uat.yaml -n app-uat
helm upgrade app-uat . -f ./values/uat.yaml -n app-uat
helm uninstall app-uat app-uat -n app-uat

docker build . -t habor.analytichpxv3.online/kubernetes-workshop/jack-api:dev

docker push habor.analytichpxv3.online/kubernetes-workshop/jack-api:dev
