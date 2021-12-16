# kustomize-ubi
A docker image based on Red Hat UBI 8.4 and kustomize to be used within Kubernetes / OpenShift 4.x

## Version History
- kustomize-ubi:4.1.3
- kustomize-ubi:4.4.0
- kustomize-ubi:4.4.1

## Content of the image
As of 4.1.3 it also includes a set of different tools to be used inside a pipeline
- Kustomize 
- yq to read from yaml-files
- jq to read from json-files
- wget
- podman
- buildah

As of 4.4.1 it now also includes httpie (httpie.io)

