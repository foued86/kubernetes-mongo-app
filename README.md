# kubernetes-mongo-app
A sample mongo application deployed within kubernetes cluster.

Client (Mongo Express) -> External Service (LoadBalancer) -> MongoExpress Pod -> Internal Service (ClusterIP) -> MongoDB Pod
