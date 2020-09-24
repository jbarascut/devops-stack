# Changelog

## [0.2.0](https://github.com/camptocamp/k8s-demo/tree/0.2.0) (2020-09-20)

[Full Changelog](https://github.com/camptocamp/k8s-demo/compare/0.1.0...0.2.0)

**Implemented enhancements:**

- Add debug target to Makefile [\#30](https://github.com/camptocamp/k8s-demo/pull/30) ([mcanevet](https://github.com/mcanevet))
- Fetch repo URL and cluster name from remote [\#35](https://github.com/camptocamp/k8s-demo/pull/35) ([mcanevet](https://github.com/mcanevet))
- Don't set ResourceQuota on demo [\#36](https://github.com/camptocamp/k8s-demo/pull/36) ([mcanevet](https://github.com/mcanevet))
- Enable Prometheus metrics for Traefik [\#38](https://github.com/camptocamp/k8s-demo/pull/38) ([mcanevet](https://github.com/mcanevet))
- Deploy prometheus-operator and kube-prometheus-stack [\#40](https://github.com/camptocamp/k8s-demo/pull/40) ([mcanevet](https://github.com/mcanevet))
- Add monitoring for ArgoCD and cert-manager [\#44](https://github.com/camptocamp/k8s-demo/pull/44) ([mcanevet](https://github.com/mcanevet))
- [grafana] Search for dashboard and datasource in all namespaces [\#49](https://github.com/camptocamp/k8s-demo/pull/49) ([mcanevet](https://github.com/mcanevet))
- Deploy Loki [\#50](https://github.com/camptocamp/k8s-demo/pull/50) ([mcanevet](https://github.com/mcanevet))

## [0.1.0](https://github.com/camptocamp/k8s-demo/tree/0.1.0) (2020-09-19)

**Implemented enhancements:**

- Deploy K3s using Terraform ([mcanevet](https://github.com/mcanevet))
- Deploy ArgoCD using `helm template ... | kubectl apply -f-` ([mcanevet](https://github.com/mcanevet))
- Deploy cert-manager using ArgoCD ([mcanevet](https://github.com/mcanevet))
- Deploy Traefik using ArgoCD ([mcanevet](https://github.com/mcanevet))
- Create initial github actions pipeline to prevent regressions ([mcanevet](https://github.com/mcanevet))