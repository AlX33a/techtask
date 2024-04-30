# techtask
Sbertech test task.
```
cd techtask
source ./start.sh
```
```
helm repo add superset https://apache.github.io/superset
```
```
helm upgrade --install --values values.yaml superset superset/superset
```
```
docker-compose up
```

ssh proxy
```
ssh -N -p 22 newuser@90.156.211.254 -L 127.0.0.1:18443:192.168.49.2:8443
```

minikube start --listen-address=0.0.0.0
minikube kubectl --config view
