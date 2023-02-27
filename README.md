# minio-helm-install

```
auth:
  rootPassword: "Passw0rd!"

defaultBuckets: "tanzubackup"

service:
  type: ClusterIP | LoadBalancer

# If ingress present - 
ingress:
  enabled: true
  hostname: minio.navneetv.com
  tls: true
  selfSigned: true
```
