
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout 584c0e90553a676f59e34053c69b9d4f74e10206
helm template . --name-template prod-helm-guestbook --include-crds
```