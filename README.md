# How To Run

## when use Jib plugin
```
mvn clean package
kubectl apply -f ./k8s
```

## when use skaffold
```
skaffold dev
```

## test

```
curl http://{k8s_cluster_ip}:30080
Hello World
```
