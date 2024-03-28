# Test chart

## Parameters

### All Parameters

Global Docker image parameters
Please, note that this will override the image parameters, including dependencies, configured to use the global value
Current available global Docker image parameters: imageRegistry, imagePullSecrets and storageClass

| Name                                         | Description                                | Value          |
| -------------------------------------------- | ------------------------------------------ | -------------- |
| `replicaCount`                               | Replica count                              | `1`            |
| `image.repository`                           | image repo                                 | `nginx`        |
| `image.pullPolicy`                           | image pull policy                          | `IfNotPresent` |
| `image.tag`                                  | Rimage tag                                 | `""`           |
| `imagePullSecrets`                           | imagePullSecrets                           | `[]`           |
| `nameOverride`                               | nameOverride                               | `""`           |
| `fullnameOverride`                           | fullnameOverride                           | `""`           |
| `serviceAccount.create`                      | serviceAccount.create                      | `true`         |
| `serviceAccount.automount`                   | serviceAccount.automount                   | `true`         |
| `serviceAccount.annotations`                 | serviceAccount.annotations                 | `{}`           |
| `serviceAccount.name`                        | serviceAccount.name                        | `""`           |
| `podAnnotations`                             | podAnnotations                             | `{}`           |
| `podLabels`                                  | podLabels                                  | `{}`           |
| `podSecurityContext`                         | podSecurityContext                         | `{}`           |
| `fsGroup`                                    | fsGroup                                    | `2000`         |
| `securityContext`                            | securityContext                            | `{}`           |
| `service.type`                               | service.type                               | `ClusterIP`    |
| `service.port`                               | service.port                               | `80`           |
| `ingress.enabled`                            | ingress.enabled                            | `false`        |
| `ingress.className`                          | ingress.className                          | `""`           |
| `ingress.annotations`                        | ingress.annotations                        | `{}`           |
| `ingress.hosts`                              | hosts                                      | `[]`           |
| `ingress.tls`                                | ingres tls                                 | `[]`           |
| `resources`                                  | resoruces                                  | `{}`           |
| `livenessProbe.httpGet.path`                 | livenessProbe.httpGet.path                 | `/`            |
| `livenessProbe.httpGet.port`                 | livenessProbe.httpGet.port                 | `http`         |
| `readinessProbe.httpGet.path`                | readinessProbe.httpGet.path                | `/`            |
| `readinessProbe.httpGet.port`                | readinessProbe.httpGet.port                | `http`         |
| `autoscaling.enabled`                        | autoscaling.enabled                        | `false`        |
| `autoscaling.minReplicas`                    | autoscaling.minReplicas                    | `1`            |
| `autoscaling.maxReplicas`                    | autoscaling.maxReplicas                    | `100`          |
| `autoscaling.targetCPUUtilizationPercentage` | autoscaling.targetCPUUtilizationPercentage | `80`           |
| `volumes`                                    | volumes                                    | `[]`           |
| `volumeMounts`                               | volumeMounts                               | `[]`           |
| `nodeSelector`                               | nodeSelector                               | `{}`           |
| `tolerations`                                | tolerations                                | `[]`           |
| `affinity`                                   | affinity                                   | `{}`           |
