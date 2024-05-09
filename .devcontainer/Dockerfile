# [Choice] Ubuntu version (use jammy on local arm64/Apple Silicon): jammy, focal
FROM mcr.microsoft.com/devcontainers/cpp:1.0.7-ubuntu-20.04

LABEL dev.containers.features="common"

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends clangd-12

# ln -s /usr/bin/clangd-12 /usr/bin/clangd