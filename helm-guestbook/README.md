
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/daudcanugerah/argocd-example-apps
# cd into the cloned directory
git checkout 3c4cc900d5219a028e6925356697c0d2e335b8ac
helm template . --name-template development-helm-guestbook --include-crds
```