# appserver

1. Build your Dockerfile.
   docker build -t webserver:latest  .

2. Deploy your application using the webserver.yaml to setup deployment, replicaset, pods and service
   kubectl apply -f webserver.yaml

3. Check your resource
Kubectl get deployments ###all the deployments on the cluster
kubectl get svc ###all the svc on the cluster
kubectl get pods ###all the pods on the cluster
kubectl get replicaset ###all the pods on the cluster
