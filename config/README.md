# config

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] config`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree config`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init config
kpt live apply config --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
