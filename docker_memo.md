```
docker run -p 8080:8080 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin --security-opt seccomp=unconfined --name keycloak-demo quay.io/keycloak/keycloak:23.0.7 start-dev
```