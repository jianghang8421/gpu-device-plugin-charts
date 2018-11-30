# NVIDIA GPU Device Plugin

**为需要部署default device-plugin的node添加label:"gpu.rancher.io/type=default"**  
**为需要部署shared device-plugin的node添加label:"gpu.rancher.io/type=shared"** 

The NVIDIA device plugin for Kubernetes is a Daemonset that allows you to automatically:  
- Expose the number of GPUs on each nodes of your cluster
- Keep track of the health of your GPUs
- Run GPU enabled containers in your Kubernetes cluster.