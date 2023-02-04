# asdf-demo

```
## prereqs
# install asdf then add plugins needed
asdf plugin add kubectl
asdf plugin add kind
# checkout git repo
git clone https://github.com/MxNxPx/asdf-demo

## multi version
# switch to old branch
git checkout multi
# cd to a cluster dir
cd clusters/dev
# instal desired versions of tools with asdf
asdf install
# create cluster and apply cronjob
kind create cluster --name $CLU_NAME
kubectl apply -f cronjob.yaml
# cd to another cluster dir
cd ../prd
# instal desired versions of tools with asdf
asdf install
# create cluster and apply cronjob
kind create cluster --name $CLU_NAME
kubectl apply -f cronjob.yaml
```

