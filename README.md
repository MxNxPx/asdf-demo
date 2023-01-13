# asdf-demo

```
## prereqs
# install asdf then add plugins needed
asdf plugin add kubectl
asdf plugin add kind
# checkout git repo
git clone https://github.com/MxNxPx/asdf-demo

## old version
# switch to old branch
git checkout old
# instal desired versions of tools with asdf
asdf install
# create cluster and apply cronjob
kind create cluster
kubectl apply -f cronjob.yaml

## new version
# switch to main branch
git checkout main
# instal desired versions of tools with asdf
asdf install
# create cluster and apply cronjob
kind create cluster
kubectl apply -f cronjob.yaml
```
