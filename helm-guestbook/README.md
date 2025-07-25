
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout 13021961ffb311cc30ba8a5e1ddc2b1850c28358
helm template . --name-template development-helm-guestbook --include-crds
```