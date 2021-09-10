# Volumes

Volumes allow you to persist data.

## "Normal" Volumes

- Volume is attached to a pod / pod lifecycle. Data is removed on pod restart.
- Defined and created together with a pod.
- Repetetive and hard to admnister on a global level.

## Persistent Volumes

- PVs are a stand alone resource not attached to a pod.
- PVs are created stand alone and claimed via a PVC
- Is defined once and used multiple times.

## Commands

- $kubectl get pv
- $kubectl get pvc
- $kubectl apply -f=pv
- $kubectl apply -f=pvc
