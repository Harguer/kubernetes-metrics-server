# kubernetes-metrics-server
Development/Learning environment deployment of metrics-server

NOTE: DO NOT USE THIS FOR PRODUCTION USE CASES.
 This is an insecure deployment for quick deployment in a learning environment.

* this is using rancher image due an issue while using the old one.
 image: rancher/metrics-server:v0.4.1
```
pi@k8-pi-master1:~ (⎈ |k8s-pi:kube-system) $ kubectl top nodes
NAME                   CPU(cores)   CPU%   MEMORY(bytes)   MEMORY%   
k8-pi-master1          494m         12%    1567Mi          20%       
k8-pi-node1            206m         5%     2617Mi          33%       
k8-pi-node2.home.lan   274m         6%     758Mi           9%        
pi@k8-pi-master1:~ (⎈ |k8s-pi:kube-system) $ 
```
