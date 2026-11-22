# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Soyef-Ahmed/argocd-example-apps
# cd into the cloned directory
git checkout b13dbbe95c48e2bc605e451321645c99cf067867
helm template . --name-template prod-helm-nginx --namespace prod --include-crds
```
