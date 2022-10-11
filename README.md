# Outline Deployment

## bootstrap

```
kustomize build init | k apply -f -
```

## Setup

```
k apply -f setup/kustomization.yaml
```
