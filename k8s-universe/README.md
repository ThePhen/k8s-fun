# Kubernetes all the things

## Hopefully...

``` sh
for s in */; do (cd $s; docker build . -t "${s}:v0.0.0"); done
kubectl apply ../k8s-universe/*.yaml
```
There's a neat SemVer util that might come in handy (link, TBD). Or, perhaps use a 'commit-ish' as the 'patch' or version.

