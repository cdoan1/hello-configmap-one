# hello-configmap-one


## Structure

| folder | description |
|--------|-------------|
| k8s | stores the application resources, in this case, the 4k configmap definitions |
| subscription | subscription, application, channel resources |

## Installation

1. `git clone`
2. `kubectl kustomize .`
3. `kubectl apply -k subscription/`

