# kind-setup
A repository holding info on a KinD cluster creation for the education/testing purposes

# Prerequisites
The following should be installed for using `kind`:
- go
- kubectl

# Installation
Check the official guide: [link](https://kind.sigs.k8s.io/). \
Or perform the following commands:
```shell
go install sigs.k8s.io/kind@v0.23.0
export PATH=$PATH:~/go/bin/
```

# Available commands
Some commands examples:
- `kind create cluster --config kind-config.yml` -- create a cluster
- `kind delete cluster` -- delete the default cluster (named `kind`)

