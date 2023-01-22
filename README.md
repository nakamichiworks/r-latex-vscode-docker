# Docker images for writing R and LaTeX in Visual Studio Code

## Release

Manually run `Docker Build and Push` workflow with the target docker image tag.



## Image tags

All images are derived from [rocker-project](https://rocker-project.org/images/) images.

### Base images (R & LaTeX)

NOTE: These images contain all of the TeXLive packages and very slow to build.

- `verse-4.2.2`
- `geospatial-4.2.2`

### VSCode imags

NOTE: These images are dependent on the corresponding base images.

- `vscode-verse-4.2.2`
- `vscode-geospatial-4.2.2`
