# Docker Files for Building Development Environment

How to build image and push to docker hub?

See: https://www.pluralsight.com/guides/create-docker-images-docker-hub


## CPP

Build a cpp dev image: 

* https://austinmorlan.com/posts/docker_clion_development/

Work with Clion: 

1. https://blog.jetbrains.com/clion/2020/01/using-docker-with-clion/
2. https://blog.jetbrains.com/clion/2021/10/clion-2021-3-eap-new-docker-toolchain/
3. https://www.jetbrains.com/help/clion/clion-toolchains-in-docker.html

## Questions

Why does docker automatically pull an `arm64` ubuntu image?

Where does clion store compiled linux binary?

> The project folder will be mounted to the Docker container and building, running, and debugging will be performed in it. CLion will start the container and shut it down after the command is executed. The project folder will be mounted into the /tmp/ProjectFolder directory in the container.

src: https://www.jetbrains.com/help/clion/clion-toolchains-in-docker.html#build-run-debug-docker

# TODO 

- [ ] build a base image, install IDE dependencies, like vscode extensions
- [ ] install vscode server and plugins
- [ ] build image for different architectures