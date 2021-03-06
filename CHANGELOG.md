# v1.2.3 / 2020-01-13

* Upgrade to Kubernetes-1.16.4
* Added support for ConfigMaps search, with command aliases:
  - configmaps, configmap, cm
* Added support for Secrets search, with command aliases:
  - secrets, secret

# v1.2.2 / 2019-12-09

* Release with LICENSE, resolved [#16](https://github.com/guessi/kubectl-grep/issues/16)

# v1.2.1 / 2019-11-15

* Upgrade to Kubernetes-1.15.6
* Fix KUBECONFIG not working issue, @tsaarni thanks ([#14](https://github.com/guessi/kubectl-grep/pull/14))
* Fix namespace not respect the setting from KUBECONFIG, reported by @fredleger ([#13](https://github.com/guessi/kubectl-grep/issues/13), [#15](https://github.com/guessi/kubectl-grep/pull/15))

# v1.2.0 / 2019-09-15

* Upgrade to Kubernetes-1.15.3
* Upgrade to Go 1.13.0
* Added support for StatefulSets search
* Added support for `-A` as the shortcut of `--all-namespaces`
* Added support for install via `kubectl krew install grep`
* Fixed `--help` not work for the root command
* Support for command aliases:
  - daemonsets, daemonset, ds
  - deployments, deployment, deploy
  - hpas, hpa
  - nodes, node, no
  - pods, pod, po
  - statefulsets, stateful, sts

# v1.1.0 / 2019-07-19

* Upgrade to Kubernetes-1.15.1
* Cleanup go.mod / go.sum
* *BREAKING CHANGE*: Renamed as `kubectl-grep`

# v1.0.5 / 2019-05-12

* Exit if `.kube/config` not found
* Code refactoring

# v1.0.4 / 2019-04-20

* Added Support for Node Search
* Upgrade to Kubernetes-1.14.1

# v1.0.3 / 2019-04-07

* Security Fixes for CVE-2019-1002101 and CVE-2019-9946

# v1.0.2 / 2019-03-22

* Supported NodeName Display for Pods
* Supported Multi-Selector Display for DaemonSets
* Don't Panic if Cluster Unreachable

# v1.0.1 / 2019-03-17

* Added Support for DaemonSets
* Added Support for "-o wide" Option
* Added Support for GO Modules

# v1.0.0 / 2019-03-09

* Initial Release
