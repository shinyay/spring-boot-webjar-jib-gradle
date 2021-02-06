# Jib for Gradle Project Template

Jib builds optimized Docker and OCI images for your Java applications without a Docker daemon.

## Description
This project is created which is based on [docker-maven-spring-boot-template](https://github.com/shinyay/docker-maven-spring-boot-template)

## Demo

```
$ ./gradlew clean jib
```

![jib-demo](https://user-images.githubusercontent.com/3072734/99399551-2d93f000-2929-11eb-976b-d995af86057f.gif)

## Features

- feature:1
- feature:2

## Requirement

## Usage

./gradlew <JIB_TASK>

```
Jib tasks
---------
jib - Builds a container image to a registry.
jibBuildTar - Builds a container image to a tarball.
jibDockerBuild - Builds a container image to a Docker daemon.
```

### Use Jib as Gradle argument
```shell script
$ ./gradlew clean jib -Djib.to.image=gcr.io/(gcloud config get-value project)/shinyay-app:1.0.0
```

## Installation

## References
- [Gradle plugins](https://plugins.gradle.org/plugin/com.google.cloud.tools.jib)

## Licence

Released under the [MIT license](https://gist.githubusercontent.com/shinyay/56e54ee4c0e22db8211e05e70a63247e/raw/44f0f4de510b4f2b918fad3c91e0845104092bff/LICENSE)

## Author

[shinyay](https://github.com/shinyay)
