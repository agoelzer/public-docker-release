# public-docker-release

temporary repo to try out github docker image release flow

# Permissions

need to set in git repo: Settings / Actions / General / Workflow Permissions / Read and write permission

# docker pull

docker pull ghcr.io/agolzer/public-docker-release:latest

# Helm install

```
$ helm repo add agolzer-helm https://agolzer.github.io/public-docker-release
$ helm search repo agolzer-helm
NAME                                    CHART VERSION   APP VERSION     DESCRIPTION
agolzer-helm/public-docker-release      0.1.4           1.16.0          A Helm chart for Kubernetes
$ helm pull agolzer-helm/public-docker-release
```
