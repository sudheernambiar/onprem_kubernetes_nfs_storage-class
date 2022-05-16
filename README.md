# onprem_kubernetes_nfs_storage-class
## Storage Class
A StorageClass is a Kubernetes resource that enables dynamic storage provisioning. 
The administrator configures the StorageClass, which can then no longer be modified. First the StorageClass is created, then the PersistentVolumeClaim and finally the Pod. When a PVC is created, Kubernetes creates a PersistentVolume and binds it to the PVC automatically, depending on the VolumeBindingMode used in the StorageClass configuration. These three Kubernetes objects are required to check the test case of a StorageClass.
