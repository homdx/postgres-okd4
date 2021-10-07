https://cloud.redhat.com/blog/a-guide-to-openshift-and-uids

# Bitnami Helm deploy to OKD 4.8+.

Tested with OKD 4.8.5

`helm install postgres12 . --namespace postgres --set image.tag=12.8.0-debian-10-r28 --set securityContext.fsGroup=1000650000,securityContext.runAsUser=1000600000 --set containerSecurityContext.runAsUser=1000650000`
