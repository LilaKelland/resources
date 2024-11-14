# To be orgainized later

## KCC
```
kpt fn render .
```
* https://github.com/seek-oss/kpt-functions/blob/master/examples/tutorial/README.md

## Find out what's consuming all the space on my cloudshell
```
du -h --max-dpeth=1 ~/
```
Usually it's npm 
```
npm cache clean --force
```
## Linting 
```
npm install -g prettier
npm install -g eslint
prettier --check .
prettier --write .
eslint .
eslint --fix .
```

## Look at next
* ArgoCD (with gitops as well)
* Kargo
* Arora/ Flux
