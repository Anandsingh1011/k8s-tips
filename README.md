# k8s-tips
k8s-tips

## General Tool 

kubernetes-cli is Kubectl. It's the CLI for talking to the Kubernetes Master and doing stuff.

helm is the best templating engine for Kubernetes manifests available. It is an industry standard.

stern is a CLI for tailing the logs of multiple pods at once.

skaffold is a CLI for building, tagging, pushing and deploying Docker containers to kuberentes in one command.

kustomize is another templating engine for YAML.

kubextx massively minimizes the effort in switching between namespaces and kubeconfigs.

kube-ps1 shows your kubeconfig in your shell.

watch is the linux style watch command for Mac.

parallel is another linux utility for Mac that let's you run Bash commands in parallel.

tree it's the one from Linux.

K9s - Kubernetes CLI To Manage Your Clusters In Style!


```
brew install kubernetes-cli && \
brew install helm && \
brew install stern && \
brew install skaffold && \
brew install kustomize && \
brew install kubectx && \
brew install kube-ps1 && \
brew install watch && \
brew install parallel && \
brew install tree
brew install k9s
```

## Debugging Tool

 [Telepresence](https://www.telepresence.io/reference/install)
 
