# free5gc-kpt

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] free5gc-kpt`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree free5gc-kpt`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init free5gc-kpt
kpt live apply free5gc-kpt --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
