# Iniciar el proyecto
   
kubectl apply -f api-service-deployment.yaml
kubectl apply -f api-service-service.yaml
kubectl apply -f faker-service-deployment.yaml
kubectl apply -f faker-service-service.yaml
kubectl apply -f database-database-env-configmap.yaml
kubectl apply -f db-deployment.yaml        
kubectl apply -f db-service.yaml 
kubectl apply -f website-deployment.yaml 
kubectl apply -f website-service.yaml 
kubectl apply -f postgres-data-persistentvolumeclaim.yaml                  
                             
