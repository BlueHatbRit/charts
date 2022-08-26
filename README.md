# Helm chart repository

This repository stores the source code _and_ published versions of my helm charts. It uses github pages to do so.

## Usage

Once helm is installed and setup correctly, add the repo as follows:

```
helm repo add bluehatbrit https://bluehatbrit.github.io/charts
```

If you've done this previously, run `helm repo update` to pull the latest versions. To see all available charts
run `helm search repo bluehatbrit`.
