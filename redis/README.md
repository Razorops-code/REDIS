#### Install helm chart dependency

```
helm dependency build
```

### Validate helm chart

```
helm lint
```

### Install/Upgrade helm chart

```
helm upgrade --install redis . --create-namespace -n redis 
```

### Uninstallhelm chart

```
helm uninstall redis -n redis
```
