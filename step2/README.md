minikube addons enable metrics-server

sudo mkdir step2 
vi deploy-servuce-hpa.yaml 
kubectl apply -f deploy-servuce-hpa.yaml 
kubectl scale deployment quakewatch-deployment --replicas=0  
kubectl get pods 



