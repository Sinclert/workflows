# GHA Workflows

This repository contains useful GitHub Actions (GHA) reusable workflows to be used
in different projects. Head to the [official documentation][doc-gha-reusable-workflows]
for further details.

### Tagging
Commits can be tagged to create _informal_ releases of the package. In order to do so:

1. Bump up the package version (`VERSION`) following [Semantic Versioning][web-semantic].
2. Create and push a tag: `make tag`.


[doc-gha-reusable-workflows]: https://docs.github.com/en/actions/using-workflows/reusing-workflows
[web-semantic]: https://semver.org/
