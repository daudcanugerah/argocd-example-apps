
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout 10ee40d15ba1fbab442b86c4c5a4b37b81c3eabb
helm template . --name-template prod-helm-guestbook --include-crds
```