## maven-openjdk

![](https://github.com/kodelint/maven-openjdk/actions/workflows/dockerfile-lint.yml/badge.svg)
![](https://github.com/kodelint/maven-openjdk/actions/workflows/build-and-push.yml/badge.svg)

`maven` docker image with base `openjdk:11.0.16-jdk`. Comes with following pre-installed

- `git=1:2.30.2-1`
- `vim-tiny=2:8.2.2434-3+deb11u1`
- `curl=7.74.0-1.3+deb11u2`
- `bash=5.1-2+deb11u1`

| **Component** | **Version** |
| --- | --- |
| `maven` | `3.8.6`|
| `openjdk` | `11.0.16`|

This repo usage [hadolint](https://github.com/hadolint/hadolint) for `Dockefile` linting process. Any push the `main` branch will trigger [dockerfile-lint](https://github.com/kodelint/maven-openjdk/blob/main/.github/workflows/dockerfile-lint.yml). For ignore certain warning please use [.hodolint.yaml](https://github.com/kodelint/maven-openjdk/blob/main/.hadolint.yaml)

**GITHUB Repo:** [cloudcli](https://github.com/kodelint/maven-openjdk)