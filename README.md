# Kubernetes-TravelAgency-Microservice-NGINX-Ingress

This project is based on project (https://github.com/VladimirMarinkovic/travel-agency-microservice) and configured for kubernetes deployment.

* **Install nginx ingress controller on kubernetes cluster** - (https://kubernetes.github.io/ingress-nginx/deploy/)

* **MySql deployment** - kubectl apply -f mysql-deployment.yaml

* **Auth Service deployment** - kubectl apply -f auth-deployment.yaml

* **Tura,Putnici,Vozaci Server deployment** - kubectl apply -f tura-deployment.yaml,putnici-deployment.yaml,vozaci-deployment.yaml 

* **Ingress deployment** - kubectl apply -f ingress.yaml

* **Rbac deployment** - kubectl apply -f rbac.yml 




#Images of project:

1.Architecture
![Architecture](https://github.com/VladimirMarinkovic/kubernetes-ta-microservice-nginx-ingress/blob/master/tura-resource-server/src/main/resources/images/TravelAgency-nginx-ingress.jpg)
