# Selectors

Taint the node
---
kubectl taint nodes <node> key1=value1:NoSchedule

kubectl taint nodes ip-192-168-33-161.ec2.internal hardware=gpu:NoSchedule
---

```
utaint
```
kubectl taint nodes ip-192-168-33-161.ec2.internal hardware=gpu:NoSchedule-


Label node

---

kubectl label nodes 
<your-node-name> disktype=ssd

kubectl label nodes 
ip-192-168-33-161.ec2.internal hardware=gpu

---

Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes