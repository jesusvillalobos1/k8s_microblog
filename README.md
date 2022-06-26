# k8s_microblog
This demo is for creating a Kubernetes cluster and deploying "microblog" app (a simple Python3 flask app that connects to a MySQL databse)

All components of deployment and services are bundled together in 2 main files: 

- One for the 'microblog' app 

- One for 'MySQL"  

&nbsp;

The only steps needs are to: 
 
1. clone the repo 

2. Start Minikube 

3. Move into the directory of the cloned repo 

4. Create the resources (first MySQL and then the microblog app) 
```
Kubectl create –f  MySQL.yml 
Kubectl create –f  microblog.yml 
```
