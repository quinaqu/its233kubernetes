# its233kubernetes
kubectl apply -f configMap.yaml
kubectl apply -f .\secrets.yaml
kubectl apply -f .\mariadb-deployment.yaml
kubectl apply -f .\phpmmyadmin-deploy.yaml

Run "minikube ip", navigate to <minikube ip>:30100

Used this tutorial series: https://mariadb.org/start-mariadb-in-k8s/