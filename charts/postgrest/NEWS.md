# 0.2.1

- Update maintainer

# 0.2.0

- BREAKING: move `podAnnotations` and `podSecurityContext` to `pod.annotations` and `pod.securityContext`
- Add `strategy`, `initContainer`, `command`, and `args` values  
- Make replicas automatically restart when secret changes
- Add liveness and readiness probes

# 0.1.1

- Make readiness probe configurable
- Change `.Values.containerPort` to 9000 (80 gives "permission denied")
- Add `.Values.pod.env` configuration option for generic environment variables
- Switch "secrets" (`dbUri` and `jwtSecret`) to be treated as secrets

# 0.1.0

- Initial version of helm chart!
