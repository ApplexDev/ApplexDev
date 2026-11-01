# Hey, I'm Applex.

**Software developer focused on Minecraft plugins, backend systems, and practical developer tools.**

I build software that solves real problems, with an emphasis on reliable behaviour, understandable configuration, maintainable code, and straightforward user experiences. Most of my public work is in Java and the Paper ecosystem, published through **[Plex Studios](https://github.com/PlexStudios)**.

[Portfolio](https://applex.oriko.lk) · [Public projects](https://github.com/PlexStudios) · [GitHub profile](https://github.com/ApplexDev)

## What I work on

- **Minecraft plugins:** gameplay systems, Paper integrations, configuration, commands, and persistent player data.
- **Backend development:** data storage, application logic, and external-service integrations.
- **Web and developer tools:** practical interfaces and utilities, including private and in-progress work.

## Technologies

| Area | Tools and technologies |
| --- | --- |
| Languages | Java, JavaScript, TypeScript, SQL |
| Minecraft | Paper API, Bukkit API, PlaceholderAPI |
| Data and integration | SQLite, REST APIs |
| Build and development | Gradle, Git, GitHub |

This is a working stack, not a list of every technology I've ever tried. The Java, Paper, PlaceholderAPI, SQLite, and Gradle work below is publicly inspectable.

## Selected projects

### [PlexDeathCoords](https://github.com/PlexStudios/PlexDeathCoords)

A lightweight death-location tracker for Paper servers. Players can retrieve their latest death coordinates, copy them from chat, or point a regular compass toward the saved location in the same world.

**Highlights:** per-player YAML storage, configurable MiniMessage output, reload validation, background persistence, and automated tests.  
**Stack:** Java, Paper API, Gradle.  
**Status:** Source version 1.1.0; check the published download page for available builds. **License:** MIT.

[Source and documentation](https://github.com/PlexStudios/PlexDeathCoords) · [Published builds](https://hangar.papermc.io/PlexStudios/PlexDeathCoords)

### [PlexKillstreaks](https://github.com/PlexStudios/PlexKillstreaks)

A configurable player killstreak system for Paper, with milestones, command rewards, anti-farming protection, leaderboards, and PlaceholderAPI integration.

**Highlights:** SQLite-backed statistics, configurable rewards and announcements, optional placeholders, and documented compatibility testing.  
**Stack:** Java, Paper API, SQLite, PlaceholderAPI, Gradle.  
**Status:** Public source for version 2.0.0. **License:** MIT.

[Source and documentation](https://github.com/PlexStudios/PlexKillstreaks) · [Modrinth](https://modrinth.com/mod/plexkillstreaks)

### [PlexVariables](https://github.com/PlexStudios/PlexVariables)

A configurable variable engine that extends PlaceholderAPI with YAML-defined values, conditions, expressions, nested references, and stored player or global data.

**Highlights:** variable-resolution safeguards, safe expression evaluation, SQLite persistence, a developer API, and transactional configuration reloads.  
**Stack:** Java, Paper API, PlaceholderAPI, SQLite, Gradle.  
**Status:** Public source-available project; check its README for current testing notes. **License:** Repository-specific restrictions apply.

[Source and documentation](https://github.com/PlexStudios/PlexVariables) · [Developer API](https://github.com/PlexStudios/PlexVariables/blob/main/docs/API.md)

## How I approach development

I prefer clear responsibilities over unnecessary abstractions, validate configuration and external input, and keep expensive I/O away from time-sensitive server work where possible. I also try to document compatibility and testing limits instead of promising that code works on versions I haven't checked.

You can inspect the implementation, configuration examples, build files, and documented trade-offs in the repositories linked above.

## Work with me

I take on selected Minecraft plugin, integration, and web-development projects. For an overview of my work and contact options, visit **[applex.oriko.lk](https://applex.oriko.lk)**.

Some commissioned work is private and isn't published without the client's permission.
