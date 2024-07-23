# COW-ECOSISTEM

Infrastructure build on kubernetes with minikube

### Author
  - *Andres Felipe Alfonso Ortiz*

### Technologies
  - *Kubernetes*: Portable and extensible open source platform for managing workloads and services.

### APPLICATIONS

##### personal apis
- [x] api-gateway-service
- [x] demo-service
- [x] sso-service

##### api utilities
- [x] keycloak
- [ ] granfana
- [ ] prometheus
- [ ] cadavisor

### Commands
__1. Kubectl__

| Description     | Value                      |
|-----------------|----------------------------|
| version         | kubectl api-version        |
| upload object   | kubectl apply -f file.yml  |
| download object | kubectl delete -f file.yml |
| see objects     | kubectl get all            |
| see object      | kubectl get pods           |

__2. Minikube__

| Description                 | Value                         |
|-----------------------------|-------------------------------|
| start minikube              | minikube start                |
| stop minikube               | minikube stop                 |
| open dashboard              | minikube dashboard            |
| get closter ip              | minikube ip                   |
| open tune by service        | minikube service file-service |
| open tunel all              | minikube tunnel               |
| delete images into minikube | minikube ssh                  |


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