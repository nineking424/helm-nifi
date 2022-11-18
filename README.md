# Helm Chart for Apache NiFi(Customized to use HTTP)
### About this repo
- I modified a few files to make Nifi use HTTP. Because NiFi 1.5.0 has been updated to use HTTPS(Modified : values.yaml, template/statefulste.yaml)

- If the LoadBalancer Service and port 8080 are available in your Kubernetes, you can use this code as it is.
- Usage :
```bash
helm install my-nifi .
```
- In you Browser
```
http://<EXTERNAL-IP>:8080/nifi
```
More informations : https://github.com/cetic/helm-nifi
