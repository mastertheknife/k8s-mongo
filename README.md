Just sharing what i found online, and slightly modified by me.
It works fine on GKE, and uses SSD storage class by default.
Remove the storageClass from the stateful set if you want to use normal storage.

No additional steps are needed, the sidecar takes care of forming the cluster.
