# k8s_microblog
At this point I simply crammed all the components together in 2 main files: 

- One for the 'microblog' app 

- One for 'MySQL"  

&nbsp;

All you gotta do, is to: 
 
1. clone the repo 

2. Start Minikube 

3. Move into the directory of the cloned repo 

4. Create the resources (first MySQL and then the microblog app) 
```
Kubectl create –f  MySQL.yml 
Kubectl create –f  microblog.yml 
```