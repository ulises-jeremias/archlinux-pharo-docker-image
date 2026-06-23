# archlinux-pharo-docker-image

Docker image for [Pharo](https://pharo.org/) Smalltalk on top of Arch Linux.

> [!IMPORTANT]
> ## Status
>
> **This project is unmaintained.** It has not received updates since 2017 and
> is not actively developed. The base image (`base/archlinux`) and the Pharo
> installer (`get.pharo.org`) it relies on have moved on, so the build may no
> longer work out of the box.
>
> For an up-to-date Pharo installation, see the official Pharo project at
> [pharo.org](https://pharo.org/) or its
> [download page](https://pharo.org/download).
>
> The Dockerfiles and scripts in this repository are intentionally left
> untouched for historical reference.

## Contents

- `Dockerfile` — base image installing the Pharo stable VM on Arch Linux.
- `seaside/` — variant image that additionally loads the
  [Seaside](https://github.com/SeasideSt/Seaside) web framework on top of the
  base image.

## License

See [LICENSE](LICENSE) for the terms of this project.