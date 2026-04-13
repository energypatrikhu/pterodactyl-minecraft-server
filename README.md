# Docker Minecraft Server for Pterodactyl Panel

This is a fork of [itzg/docker-minecraft-server](https://github.com/itzg/docker-minecraft-server) customized for use with Pterodactyl Panel.

## Pterodactyl Eggs

Pterodactyl Panel eggs for this image can be found in [the eggs directory](eggs) of this repo:

- [Vanilla](eggs/egg-itzg-vanilla.json)
- [Forge](eggs/egg-itzg-forge.json)
- [Fabric](eggs/egg-itzg-fabric.json)
- [NeoForge](eggs/egg-itzg-neoforge.json)
- [CurseForge](eggs/egg-itzg-curseforge.json)
- [Modrinth](eggs/egg-itzg-modrinth.json)
- [FTB](eggs/egg-itzg-ftb.json)

> **Note:** The eggs contain the minimal required environment variables. For a complete list of all supported environment variables, please refer to the [documentation](https://docker-minecraft-server.readthedocs.io/).

## Original README

[![GitHub Issues](https://img.shields.io/github/issues-raw/energypatrikhu/pterodactyl-minecraft-server.svg)](https://github.com/energypatrikhu/pterodactyl-minecraft-server/issues)
[![Discord](https://img.shields.io/discord/660567679458869252?label=Discord&logo=discord)](https://discord.gg/DXfKpjB)
[![Build and Publish](https://github.com/energypatrikhu/pterodactyl-minecraft-server/actions/workflows/build.yml/badge.svg)](https://github.com/energypatrikhu/pterodactyl-minecraft-server/actions/workflows/build.yml)
[![](https://img.shields.io/badge/Donate-Buy%20me%20a%20coffee-orange.svg)](https://www.buymeacoffee.com/itzg)
[![Documentation Status](https://readthedocs.org/projects/docker-minecraft-server/badge/?version=latest)](https://docker-minecraft-server.readthedocs.io/en/latest/?badge=latest)

 [![Read the docs](docs/img/banner-docs.png)](https://docker-minecraft-server.readthedocs.io/)

There you will find things like
- [Quick start with Docker Compose](https://docker-minecraft-server.readthedocs.io/en/latest/#using-docker-compose)
- Running [different versions of Minecraft](https://docker-minecraft-server.readthedocs.io/en/latest/versions/minecraft/) and using [various server types](https://docker-minecraft-server.readthedocs.io/en/latest/types-and-platforms/) for Java Edition
- [Setting server properties via container environment variables](https://docker-minecraft-server.readthedocs.io/en/latest/configuration/server-properties/)
- [Managing mods and plugins with automated downloads and cleanup](https://docker-minecraft-server.readthedocs.io/en/latest/mods-and-plugins/)
- [Using various modpack providers/platforms](https://docker-minecraft-server.readthedocs.io/en/latest/types-and-platforms/)
- ...and much more

There are also many examples located in [the examples directory](examples) of this repo.

This image only supports Java edition natively; however, if looking for a server that is compatible with Bedrock edition, then use [itzg/minecraft-bedrock-server](https://github.com/itzg/docker-minecraft-bedrock-server) or [refer to this section](https://docker-minecraft-server.readthedocs.io/en/latest/misc/examples/#bedrock-compatible-server) to add Bedrock compatibility to a Java edition server.

[![Sponsors](docs/img/banner-sponsors.png)](#sponsors)

<a name="sponsors"></a>

<a href="https://spawnbox.app"><img src="https://spawnbox.app/favicon-48x48.png" alt="SpawnBox logo" width="48" align="left" /></a>

<a href="https://spawnbox.app"><b>SpawnBox</b></a> - Powered by <code>itzg/minecraft-server</code>, it's a Windows desktop app for parents, teens, and friend groups who want a Minecraft server on their own PC without learning Docker, WSL2, or networking.

<br clear="left" />

<a href="https://server.pro"><img src="https://server.pro/s/img/logo-short-192.png" alt="Server.pro logo" width="48" align="left" /></a>

<a href="https://server.pro"><b>Server.pro</b></a> - A game server hosting platform offering one-click Minecraft server deployment powered by <code>itzg/minecraft-server</code>, with global locations and an easy-to-use control panel.

<br clear="left" />

<!-- additional sponsors repeat the pattern above: floated logo + blurb + clear-left break -->
<!-- logo image preferrably hosted on an external, stable site at a size of 48x48px -->
<!-- link to sponsor site -->
<!-- one or two line summary ideally with a mention of image integration -->

[and more...](https://github.com/sponsors/itzg)
