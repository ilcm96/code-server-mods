# JetBrain Mono - Docker mod for code-server and openvscode-server

This mod adds a JetBrains Mono font to code-server and openvscode-server, to be installed/updated during container start.

In code-server or openvscode-server docker arguments, set an environment variable `DOCKER_MODS=ghcr.io/ilcm96/code-server-mods:code-server-jetbrains-mono`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ghcr.io/ilcm96/code-server-mods:code-server-jetbrains-mono|linuxserver/mods:code-server-mod`
