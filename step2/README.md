minikube addons enable metrics-server

sudo mkdir step2 
vi deploy-servuce-hpa.yaml 
kubectl apply -f deploy-servuce-hpa.yaml 

kubectl get pods 
kubectl get hpa


kubectl create configmap quakewatch
kubectl get cm quakewatch -o yaml


kubectl scale deployment quakewatch-deployment --replicas=0 
