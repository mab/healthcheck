# healthcheck

Minimal example to create `livenessProbe` and `readinessProbe` into the `kubernetes.yml` by 
the fabric8 / [jkube](https://github.com/eclipse/jkube) plugin.

```
mvn clean process-resources
```

The generated kubernetes descriptior can be found under `target/classes/META-INF/fabric8/kubernetes.yml`.
