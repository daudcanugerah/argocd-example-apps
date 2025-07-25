
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout 8ade04da1c03eaa832717103af0d1195b591f03e
helm template . --name-template development-helm-guestbook --include-crds
```