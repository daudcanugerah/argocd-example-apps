
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout 7f1bb4083c49749a1dd3fa8d12168d50ad886513
helm template . --name-template development-helm-guestbook --include-crds
```