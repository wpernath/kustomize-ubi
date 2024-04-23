# Kustomize-ubi / toolbox-ubi
A container image based on Red Hat UBI 8.9 minimal to be used for demo purposes.

## Content of the image
Originally just a simple kustomize container image, it's now a toolbox image, which I am using in my CI/CD chains. It contains the following tools:

- based on Red Hat UBI minimal 8.9
- Adds `Kustomize` (right now v5.4.1)
- Adds `yq` to read from YAML files
- Adds `jq` to read from JSON files
- Adds `wget` & `curl`
- Contains `httpie` [httpie.io](https://httpie.io/) client as a better curl replacement
- Contains `kubectl` (Kubernetes Client)

## Version History
- kustomize-ubi:4.1.3
- kustomize-ubi:4.4.0
- kustomize-ubi:4.4.1
- kustomize-ubi:4.5.2
- kustomize-ubi:4.5.5
- kustomize-ubi:4.5.7
- kustomize-ubi:5.4.1

As of v4.4.1 it now also includes httpie (httpie.io)

As of v4.5.2 it now also includes kubectl (Kubernetes client)



## Dockerfile
The docker file can be found here: [https://github.com/wpernath/kustomize-ubi](https://github.com/wpernath/kustomize-ubi)

## Examples
Have a look at the following repositories on GitHub:
- [https://github.com/wpernath/book-example](https://github.com/wpernath/book-example)
- [https://github.com/wpernath/person-service-config](https://github.com/wpernath/person-service-config)
- [https://github.com/wpernath/simple-quarkus](https://github.com/wpernath/simple-quarkus)
- [https://github.com/wpernath/quarkus-grumpycat](https://github.com/wpernath/quarkus-grumpycat)

## Image
You can find the image on [https://quay.io](https://quay.io/wpernath/kustomize-ubi)

```bash
$ docker pull quay.io/wpernath/kustomize-ubi
```
