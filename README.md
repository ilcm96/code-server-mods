# Change Extension Gallery - Docker mod for code-server and openvscode-server

This mod changes extension gallery to Microsoft's extension gallery to to code-server and openvscode-server, to be installed/updated during container start.
In code-server or openvscode-server docker arguments, set an environment variable `DOCKER_MODS=ghcr.io/ilcm96/code-server-mods:code-server-change-extension-gallery`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ghcr.io/ilcm96/code-server-mods:code-server-change-extension-gallery|linuxserver/mods:code-server-mod`
