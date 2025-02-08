**Streaming logs of a certain pod**
kubectl logs -f <yourpod_name> => grade-submission-portal

**Port Forward method to expose your pod into localhost/current server**
kubectl port-forward <yourpod_name> => grade-submission-portal 8080:5001

**using label selector for any kubectl commands**
kubectl command pod -l "app.kubernetes.io/name=<name>"