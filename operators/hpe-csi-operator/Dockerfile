FROM quay.io/operator-framework/helm-operator:v1.0.0
LABEL name="csi-driver-operator" \
      maintainer="HPE Storage Containers Team" \
      vendor="HPE" \
      version="1.0.0" \
      release="1.0" \
      summary="HPE CSI Operator" \
      description="HPE CSI Operator for Kubernetes" \
      io.k8s.display-name="HPE CSI Operator for Kubernetes" \
      io.k8s.description="The HPE CSI Operator for Kubernetes enables container orchestrators, such as Kubernetes and OpenShift, to manage the life-cycle of persistent storage." \
      io.openshift.tags=hpe,csi,hpe-csi-driver

COPY helm-charts/ ${HOME}/helm-charts/
COPY watches.yaml ${HOME}/watches.yaml
COPY LICENSE /licenses/
