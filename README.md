# SM64 TAS Archive
This repository serves to archive the critical milestones throughout SM64 TASing history. This repository stores TAS WR files for ILs, ABC, and full category runs.

## About this repository
Anyone is free to use this repository. If you have an improved TAS, wish to add a TAS currently not archived, etc., you can make a pull request. Alternatively, you can join the [Super Mario 64 TASing and ABC](https://discord.gg/ECskvyF) Discord server and contact me, TimeTravelPenguin.

## How to contribute?
If you have files you wish to contribute, you can either contact me or merge them yourself. To do so, fork this branch - this will create a clone of the repository - add those changes to your forked branch, then return here and select `New Pull Request`. Then choose this repository's master branch as the base, and your forked repo as the head. Then merge! Make sure you comment on your changes when you commit! It helps a lot to ensure correct mergers. Thanks!

## Repository structure
As this repository grows, the structure and layout surely will, also. For now, it will be as follows:
```
Root
 - ABC
 - Full Category
 - IL
```
From there, each directory should contain a collection of folders, each representing the data provided.
For IL related files, the address should look like `~/IL/BoB/Behind-Chain-Chomps-Gate/{TAS time}`.
Or, further succinctly, as `~/IL/{Level}/{Star}/{TAS time}`.

For full category related files, it should be stored as `~/Full-Category/{Category}/{TAS Time}`.
`{TAS time}` should be in `#m#s#ms` notation. For example, a TAS of 201.5 seconds should be `3m21s50ms`, rounding the ms to 2d.p.

## Why make this repository?
Tool-assisted speedrunning has been a big part of my life. Newcomers and non-TASers deserve equal access to resources as any other member of the community. However, without understanding the community's structure, accessing TASing information is almost impossible in many cases. So, I have made it my mission to build this library as a way of allowing an easy-access means of locating the verified resources.

## Other important resources
1. [STROOP](https://github.com/SM64-TAS-ABC/STROOP)

STROOP is a diagnostic tool for Super Mario 64 that displays and allows for simple editing of various game values and information. It can connect to a running emulator and update values in real time. Some core features include views of loaded/unloaded objects, Mario structure variables, camera + HUD values, an overhead map display, and many more.

2. [Ukikipedia](https://ukikipedia.net/wiki/Main_Page)

This wiki is dedicated to recording expert level knowledge of Super Mario 64. The purpose of this wiki is to allow people to find information that isn't easily available on other websites or by a quick Google search.

Please join the [Super Mario 64 TASing and ABC](https://discord.gg/ECskvyF) Discord server for any other SM64 TASing related matters!
