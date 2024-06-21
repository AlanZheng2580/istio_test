# istio_test

## How to get the list of virtual_hosts

```
kubectl exec -it httpbin-0 -c istio-proxy -- curl http://localhost:15000/config_dump|grep -A 10 virtual_hosts
```
