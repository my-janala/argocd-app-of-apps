# argocd-app-of-apps


## Name
ArgoCD-App-of-Apps.

## Repo Structure 

```angular2html
my-argo-repo/
├── helm-charts/
│   └── bookinfo/
│       ├── Chart.yaml
│       ├── templates/
│       │   ├── productpage-deployment.yaml
│       │   ├── details-deployment.yaml
│       │   ├── reviews-deployment.yaml
│       │   ├── ratings-deployment.yaml
│       │   ├── service.yaml
│       └── values.yaml
│       └── overlays/
│           ├── dev/
│           │   └── values-dev.yaml
│           ├── staging/
│           │   └── values-staging.yaml
│           └── prod/
│               └── values-prod.yaml
├── projects/
│   ├── dev/
│   │   └── bookinfo-project.yaml
│   ├── staging/
│   │   └── bookinfo-project.yaml
│   └── prod/
│       └── bookinfo-project.yaml
├── applications/
│   ├── dev/
│   │   └── bookinfo.yaml
│   ├── staging/
│   │   └── bookinfo.yaml
│   └── prod/
│       └── bookinfo.yaml
└── bootstrap/
    └── root-app.yaml

```

## Description


## Roadmap
If you have ideas for releases in the future, it is a good idea to list them in the README.


## License
For open source projects, say how it is licensed.

## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
