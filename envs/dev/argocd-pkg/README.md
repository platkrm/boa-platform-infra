# argocd-pkg

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] argocd-pkg`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree argocd-pkg`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init argocd-pkg
kpt live apply argocd-pkg --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
