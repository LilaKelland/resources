# To be orgainized later

## gcloud
```
gcloud config set project
gcloud services list --enabled
kubtctil get namespace
```

## KCC
```
kpt fn render .

first need to gcloud services enable serviceusage.googleapis.com

```
* https://github.com/seek-oss/kpt-functions/blob/master/examples/tutorial/README.md
* https://cloud.google.com/config-connector/docs/how-to/getting-started
* https://developers.google.com/apis-explorer

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
## GCP 
* https://cloud.google.com/artifact-registry/docs/analysis
* https://cloud.google.com/artifact-analysis/docs/sbom-overview



## Look at next
* ArgoCD (with gitops as well)
* Kargo
* Arora/ Flux

AI tools 
* Grok2
* Claude developer
* cursor AI code editor

## Screen Reader 
* shift to step through
