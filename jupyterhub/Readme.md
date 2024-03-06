## Setup jupyter hub

## 
* helm repo add jupyterhub https://jupyterhub.github.io/helm-chart/
* helm upgrade --install my-jupyterhub jupyterhub/jupyterhub --version 3.2.2-0.dev.git.6528.h377e69e7 -n jupyter --values jupyterhub.yaml
* helm uninstall my-jupyter