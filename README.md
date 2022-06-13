# Kustomize-ubi / toolbox-ubi
A docker image based on Red Hat UBI 8.5 minimal to be used for demo purposes.

## Content of the image
Originally just a simple kustomize container image, it's now a toolbox image, which I am using in my CI/CD chains. It contains the following tools:

- based on Red Hat UBI minimal 8.6
- Adds `Kustomize` (right now v4.5.5)
- Adds `yq` to read from YAML files
- Adds `jq` to read from JSON files
- Adds `wget` & `curl`
- Contains `httpie` [httpie.io](url) client as a better curl replacement
- Contains `kubectl` (Kubernetes Client)

## Version History
- kustomize-ubi:4.1.3
- kustomize-ubi:4.4.0
- kustomize-ubi:4.4.1
- kustomize-ubi:4.5.2
- kustomize-ubi:4.5.5

As of v4.4.1 it now also includes httpie (httpie.io)

As of v4.5.2 it now also includes kubectl (Kubernetes client)

## Dockerfile
The docker file can be found here: [https://github.com/wpernath/kustomize-ubi](url)

## Examples
Have a look at the following repositories on GitHub:
- [https://github.com/wpernath/book-example](url)
- [https://github.com/wpernath/person-service-config](url)
- [https://github.com/wpernath/simple-quarkus](url)

## Image
You can find the image on [https://quay.io](url)

```bash
$ docker pull quay.io/wpernath/kustomize-ubi
```
