# Service Mesh Homework


## OCP Open API URL, user & password

    - OCP API URL:  https://api.cluster-sodim-66de.sodim-66de.example.opentlc.com:6443 
    - User:         opentlc-mgr
    - Password:     r3dh4t1!

    - This in RHPDS environment available until 14-Dec-2019, I will try to keep the cluster up, but in case the cluster is down let me know to start it.


## Service Mesh Installation

    For this homework I installed OpenShift Service Mesh on an OpenShift cluster version 4.2, based on the instructions of the link https://access.redhat.com/documentation/en-us/openshift_container_platform/4.2/html/service_mesh/service-mesh-installation. Service Mesh Control Planed was installed in the namespace bookretail-istio-system

    
## Homework requirements

    Based on the homework instructions I installed the bookinfo application (https://raw.githubusercontent.com/istio/istio/1.4.0/samples/bookinfo/platform/kube/bookinfo.yaml) on the bookinfo namespace.

    To accomplish the homework requirements I created a bash script named serviceMeshHomework.sh, this file have several functions to create and configure the assets required to fullfill the homework goals.

    The main URL for the bookinfo application after configure all its services to work with Service Mesh is https://productpage-service.bookinfo.apps.cluster-sodim-66de.sodim-66de.example.opentlc.com/, you can try it using 'curl -k https://productpage-service.bookinfo.apps.cluster-sodim-66de.sodim-66de.example.opentlc.com/productpage?u=normal'

    

