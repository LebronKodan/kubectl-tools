# kubectl-tools
Some handy tools to improve productivity.

Here is a list of tools which used to simplify daily k8s administration works.

- [krew](https://github.com/kubernetes-sigs/krew "krew"): a plugin manager for kubectl
- kube-ns: list and switch namespace
- kube-context: list and switch context
- kube-enter: enter a given pod with command `/bin/bash`
- kube-events: list events related to given resource
- [kube-ps1](https://github.com/jonmosco/kube-ps1 "kube-ps1"): add context and namespace info to prompt strings

By imitating the code style of `kube-ns`, `kube-context, kube-enter, kube-events` are created.

When you find that the daily operations with kubectl are cumbersome, you should consider simplifying the works with plugin.

You can first look at the [krew plugin list](https://github.com/kubernetes-sigs/krew-index/blob/master/plugins.md "krew plugin list"). If no plugins can meet your requirement, then you can do it by yourself. The [official document](https://kubernetes.io/docs/tasks/extend-kubectl/kubectl-plugins/ "official document") has given you a good example.
