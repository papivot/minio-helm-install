# minio-helm-install

```
auth:
  rootPassword: "Password"

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
