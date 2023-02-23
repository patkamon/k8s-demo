# k8s-demo

1. `minikube start`
2. deploy config and secret first `kubectl apply -f mongo-config.yaml` & `kubectl apply -f mongo-secret.yaml`
3. `kubectl apply -f mongo.yaml`
4. `kubectl apply -f web-app.yaml`

In case can't find which port `kubectl port-forward deployment/webapp-deployment 28015:3000`
