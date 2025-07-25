
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout 1788c4518da3a796df840e00f044c950889b95b5
helm template . --name-template staging-helm-guestbook --include-crds
```