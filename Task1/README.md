📋 Description Create a Pod running Nginx with custom configuration and storage, exposed via a ClusterIP service.

🛠️ Components Used Pod: Runs Nginx container

ConfigMap: Changes Nginx port from 80 to 82

PersistentVolume (PV): Provides hostPath storage

PersistentVolumeClaim (PVC): Claims storage from PV

Service: ClusterIP for internal access
