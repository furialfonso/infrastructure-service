# COW-ECOSISTEM

Infrastructure build on kubernetes with minikube

  * https://whimsical.com/cow-XkzoMTqYJ3V1rBVFw9C3tR

### Author
  - *Andres Felipe Alfonso Ortiz*

### Technologies
  - *Kubernetes*: Portable and extensible open source platform for managing workloads and services.

### APPLICATIONS

##### personal apis
- [x] api-gateway-service: https://github.com/furialfonso/api-gateway-service
- [x] demo-service: https://github.com/furialfonso/demo-service
- [x] sso-service: https://github.com/furialfonso/sso-service
- [x] cow-comp-front: https://github.com/furialfonso/cow-comp-front
- [x] cow-front: https://github.com/furialfonso/cow-front

##### api utilities
- [x] keycloak
- [x] granfana
- [x] prometheus
- [X] cadavisor

### Commands
__1. Kubectl__

| Description       | Value                             |
|-------------------|-----------------------------------|
| version           | kubectl api-version               |
| upload object     | kubectl apply -f file.yml         |
| delete object     | kubectl delete -f file.yml        |
| see objects       | kubectl get all                   |
| see object        | kubectl get pods                  |
| upload/delete all | kubectl apply/delete -f directory |

__2. Minikube__

| Description                 | Value                         |
|-----------------------------|-------------------------------|
| start minikube              | minikube start                |
| stop minikube               | minikube stop                 |
| delete instance minikube    | minikube delete               |
| open dashboard              | minikube dashboard            |
| get closter ip              | minikube ip                   |
| open tune by service        | minikube service file-service |
| open tunel all              | minikube tunnel               |
| delete images into minikube | minikube ssh                  |


__3. Grafana__

| Description       | Value                                                                 |
|-------------------|-----------------------------------------------------------------------|
| RPM               | sum by (path) (rate(http_requests_total{job="sso-service"}[1m]) * 60) |
|                   |                                                                       |
### Keycloak
  - Documentation
    - https://www.keycloak.org/documentation
  - Configuration
    - https://www.youtube.com/watch?v=zR3igUft1KA&t=2044s
    - https://medium.com/@kaloyanmanev/bitnami-keycloack-inside-docker-compose-import-realm-on-startup-3627a7da7f39


prometheus
https://www.youtube.com/watch?v=PCJwJpbln6Q
loki no funciona
https://www.youtube.com/watch?v=gD1zUESRucs
https://linuxblog.xyz/posts/grafana-loki/