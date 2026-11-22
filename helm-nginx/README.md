# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Soyef-Ahmed/argocd-example-apps
# cd into the cloned directory
git checkout a98fceb6de3ef1b7e0cb6658ffceab72bb176993
helm template . --name-template staging-helm-nginx --namespace staging --include-crds
```
