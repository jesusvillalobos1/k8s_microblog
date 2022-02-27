# k8s_microblog
running microblog app in docker containers managed with K8s

1. Start minikube 

2. login to docker in terminal to have access to docker registry to get the image

```
Docker login 
```

3. go to the directory for deployment and services files

```
cd ~/Downloads/microblog_projects/k8s_microblog

```

4. create deployment
```
k create -f K8_deployment.yml 
```

5. create service
```
k create -f k8_Service.yml  
```

6. for the 'load balancer' type service, make the Service accessible through the minikube service command
```
minikube service microblogservice 
```