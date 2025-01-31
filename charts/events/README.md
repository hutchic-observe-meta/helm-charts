# events

![Version: 0.1.17](https://img.shields.io/badge/Version-0.1.17-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: v0.10.0](https://img.shields.io/badge/AppVersion-v0.10.0-informational?style=flat-square)

Observe kubernetes event collection

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| Observe | <support@observeinc.com> |  |

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| file://../endpoint | endpoint | 0.1.7 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| customLabels | object | `{}` |  |
| global.observe | object | `{}` |  |
| image.kube_cluster_info.pullPolicy | string | `"Always"` |  |
| image.kube_cluster_info.repository | string | `"observeinc/kube-cluster-info"` |  |
| image.kube_cluster_info.tag | string | `""` |  |
| image.kube_state_events.pullPolicy | string | `"Always"` |  |
| image.kube_state_events.repository | string | `"observeinc/kube-state-events"` |  |
| image.kube_state_events.tag | string | `""` |  |
| imagePullSecrets | list | `[]` |  |
| rbac.create | bool | `true` |  |
| resources.limits.cpu | string | `"50m"` |  |
| resources.limits.memory | string | `"256Mi"` |  |
| resources.requests.cpu | string | `"50m"` |  |
| resources.requests.memory | string | `"256Mi"` |  |
| serviceAccount.annotations | object | `{}` |  |
| serviceAccount.create | bool | `true` |  |
| serviceAccount.name | string | `nil` |  |
| tolerations | object | `{}` |  |
| useJob | bool | `false` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.3](https://github.com/norwoodj/helm-docs/releases/v1.11.3)
