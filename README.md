# Helm3

This repository contains packaged Helm charts provided by C.SCOTTI for training 

# Add Repository (stable)
```
helm repo add cscotti-stable https://cscotti.github.io/Helm3/stable
helm repo update
```



# helm package commande
```
helm package ./rundeck
helm repo index --url https://cscotti.github.io/Helm3/stable ./rundeck
helm repo index --url https://cscotti.github.io/Helm3/stable --merge index.yaml ./stable

```
