
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout 3b990998bfc9c2eddf88e00d51a5fa70026ebadb
helm template . --name-template development-helm-guestbook --include-crds
```