
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout b71868cd9ad6993f8b39c0c5605d4ad9ee7b26a1
helm template . --name-template development-helm-guestbook --include-crds
```