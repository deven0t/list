## Task 

1. Try running Daemonset, Cronjob, jobs, deployment and standalone pod in kubernetes cluster. Observe the names of Controller (DS, cronjob, job, etc). Name of pod. 
2. Run Postgress db in kubernetes and access it from outside cluster, you should be able to create table in that db. 

3. Simple Application 
> a. Create on application which will serve Rest endpoint /hello with response as system time and hit count (request counts) 
b. Dockerise your application
c. Deploy Your application in Kubernetes cluster as a deployment with 2 replicas 
d. Try to access your application from outside the cluster 
e. Check the response of endpoint. 
f. Can you run your docker image as non-root user? 
g. Can you make your image without root user? 

4. Run Wordpress application in kubernetes cluster and access its UI 

5. Try running KubeHunter against your cluster https://github.com/aquasecurity/kube-hunter 

6. Try running KubeBench against your nodes https://github.com/aquasecurity/kube-bench 

7. Try running scanning images using trivy https://github.com/aquasecurity/trivy scan your image created in step no 3. 

8. Try to run starboard in your cluster and see configauditReport CRD generated in cluster using polaris plugin. 
9.  Read on  https://github.com/kubernetes-sigs/controller-runtime
>Build small application using controller runtime and keep on printing the namespaced name of pod in terminal


#### You can install kind cluster in your local to play with Kubernetes cluster. https://kind.sigs.k8s.io/ 
>Can you run multi node cluster using kind cluster 
Can you load images from your system into kind cluster to run pod using that image 

 