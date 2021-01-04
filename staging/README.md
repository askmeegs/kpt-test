# staging

## Description
STAGING

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] staging`
Details: https://googlecontainertools.github.io/kpt/reference/pkg/get/

### View package content
`kpt cfg tree staging`
Details: https://googlecontainertools.github.io/kpt/reference/cfg/tree/

### List setters
`kpt cfg list-setters staging`
Details: https://googlecontainertools.github.io/kpt/reference/cfg/list-setters/

### Set a value
`kpt cfg set staging NAME VALUE`
Details: https://googlecontainertools.github.io/kpt/reference/cfg/set/

### Apply the package
```
kpt live init staging
kpt live apply staging --reconcile-timeout=2m --output=table
```
Details: https://googlecontainertools.github.io/kpt/reference/live/
