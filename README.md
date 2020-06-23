# WeLoveOpenSourcePlugins

**This document is still work in progress and incomplete.**

*WeLoveOpenSourcePlugins* is an organisation aimed at creating and maintaining open source plugins for the [Minecraft](https://minecraft.net) server software [Spigot](https://www.spigotmc.org/) and all of its descendants/forks such as [Paper](https://papermc.io) or [Taco](https://tacospigot.github.io/).

## Rationale

Minecraft fascinates millions people to this day and Spigot has grown to be its most popular server software among end-users and developers alike. The demand for plugins that provide various enhancements and modifications of all kinds is still very high, new plugins are created and published every day. Spigot is especially popular among young and novice developers, often because it enables them to see their progress in an environment they know and love.

While many big and popular Spigot plugins *are* open source, we think that there should be more of them. Too many plugins restrain their potential by being closed source and sometimes even obfuscated, ironically while their builds are distributed freely. We see two primary factors in this observation: 

1. People simply haven't used open source before and wouldn't know how

2. People fear that their plugins may get stolen, modified or redistributed - a fear that, most of the time, is completely unjustified and based on a narrow-minded view on software development

On the other hand, we unfortunately find many *paid* plugins to be compensating for their lack of quality with a high price and uncooperative developers. This is not to say that all paid plugins are bad or that we are strictly against any form of monetisation - but we believe that many plugins *should* be free and *can* be improved with the help of open source.

*WeLoveOpenSourcePlugins* was created in an effort to bring more open source into the Spigot developer community. The main goals of the project are:

- Making more free plugins available to the Spigot community

- Getting more developers to discover and endorse open source

- Motivating developers to collaborate and cooperate

The project welcomes developers of all experience. Together we can learn and build better plugins.

## Project Requirements and Guidelines

Generally, when contributing to WLOSP, you are free to structure your project in whatever way you prefer. For example, while it is common practice, you need not take inspiration from a paid plugin for your project. Neither do we restrict you to use any particular language, library or framework. The only (and obvious) requirement is that your project is a *Spigot* plugin or a plugin for any of its forks. 

However, there are a few guidelines that your project **must** conform to:

- It must be licensed under an open source license

- The entire project must be open source, not just parts (such as an API) of it

- You must respect and enforce the [Code of Conduct](./CODE-OF-CONDUCT.md) for the project

- The project must at least be (at mods' discretion)

  - under active development or

  - in an already usable/finished state

- When released, the project must have *some* sort of documentation 

Additionally, projects that meet these criteria are strictly prohibited:

- Malicious software, including plugins that
  - unsolicitely modify/corrupt/delete files on the installed server

  - (intentionally) crash/stress clients or servers that have not consented

  - otherwise intend to harm clients or servers in any way or hide features from users

Developers whose projects violate these guidelines will be notified (e.g. via an issue). If the issue(s) cannot or will not be resolved, the project and thus the repository may be removed from the organisation. Projects may also be removed for reasons that are not listed here (yet). Such cases will be communicated exhaustively.

### Core Projects

Aside from the aforementioned requirements, there are extra steps to take if you want your project to be distributed and published under the name of *WeLoveOpenSourcePlugins*. 

- Sophisticated documentation and guides must be available in English

- The plugin's code must reach certain standards (it will be reviewed)

- The project must adopt the structures used by WLOSP, including

  - group id

  - SpigotMC account for publishing

  - dedicated Maven repository for Maven publications

## How to Join

Anyone can join this organisation, provided that they have one or more repositories/projects that they intend to create/move here. Simply create an issue in this repository outlining what you would like to contribute and you will be invited.

## Helpful Resources

### Project Template

*An example template for upcoming WLOSP projects will follow here*

### Learning

*A list of resources about programming, Spigot, git etc. will follow here*

### Tools

*A list of useful tools, libraries and frameworks for plugin development will follow here*
