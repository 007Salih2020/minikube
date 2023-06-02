▬▬▬▬▬▬  L I N K S  🔗▬▬▬▬▬▬ 
Git Repo to follow along the demos:        ►  https://gitlab.com/nanuchi/k8s-in-1-hour
Minikube Installation Guides:              ►  https://minikube.sigs.k8s.io/docs/start/
 
 kubernetes.io 
 hub.docker.com 

 

# start MiniKube in Docker container
minikube start  --driver docker

# check the status of minikube 
minikube status

# check the kubectl 
kubectl get nodes 

# #  minikube cmd is just for start up / deleting the cluster, the rest will be done through kubectl

# deploy MongoDB db &b web app, which will connect to the MongoDB db using external config data from config map & secret 
# web app is accessible externally ! 
