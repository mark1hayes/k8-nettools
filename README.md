# k8-nettools

```bash
kubectl run alpine-nettools --image=raesene/alpine-nettools 
 
kubectl logs alpine-nettools (Get passsword)
 
kubectl get pods -o wide
alpine-nettools = 172.16.0.136 
 
ssh root@172.16.0.136
root@172.16.0.136's password: 
Welcome to Alpine!


kubectl get service
NAME                  TYPE           CLUSTER-IP       EXTERNAL-IP   PORT(S)        AGE
alpine-nettools-svc   LoadBalancer   172.17.23.204    10.63.1.14    22:32493/TCP   137m

FROM EXTERNAL..
ssh root@10.63.1.14
root@10.63.1.14's password: 
Welcome to Alpine!
```
