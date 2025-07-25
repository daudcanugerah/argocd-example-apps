
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout b727eea95732017c8b45e10ebaca4cb92cee25d6
helm template . --name-template staging-helm-guestbook --include-crds
```