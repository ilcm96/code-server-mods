# nvm - Docker mod for code-server and openvscode-server

This mod adds a nvm to code-server and openvscode-server, to be installed/updated during container start.

In code-server or openvscode-server docker arguments, set an environment variable `DOCKER_MODS=ghcr.io/ilcm96/code-server-mods:code-server-nvm`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ghcr.io/ilcm96/code-server-mods:code-server-nvm|linuxserver/mods:code-server-mod`
