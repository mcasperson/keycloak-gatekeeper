See https://stackoverflow.com/questions/53700118/using-keycloak-gateway-in-a-k8s-cluster for a description of the problem this fork fixes.

* Build with `CGO_ENABLED=0 GOOS=linux GOARCH=amd64 go build`
* Build image with ` docker build . -t mcasperson/keycloak-gatekeeper:<version>`
* Push with `docker push mcasperson/keycloak-gatekeeper:<version>`