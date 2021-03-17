# Kubernetes Hello World
A Kubernetes Hello World Project for Python Flask.  This project uses [a simple Flask app that returns correct change](https://github.com/noahgift/flask-change-microservice) as the base project and converts it to Kubernetes.

## Assets in Repo

* `Makefile`:  Builds project
* `Dockerfile`:  Container configuration
* `app.py`:  Flask app


## Get Started

* Create Python virtual environment `python3 -m venv ~/.kube-hello && source ~/.kube-hello/bin/activate`

## Running Kubernetes Locally

* Install [Docker Desktop](https://www.docker.com/products/docker-desktop)

```bash
(.kube-hello) ➜  kubernetes-hello-world-python-flask git:(main) kubectl get nodes
NAME             STATUS   ROLES    AGE   VERSION
docker-desktop   Ready    master   30d   v1.19.3
```


## References

* Azure [Kubernetes deployment strategy](https://azure.microsoft.com/en-us/overview/kubernetes-deployment-strategy/)

* Service [Cluster Config](https://kubernetes.io/docs/tasks/access-application-cluster/service-access-application-cluster/) YAML file