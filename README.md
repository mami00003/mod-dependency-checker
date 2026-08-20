# Minecraft Mod Dependency Checker

A single-page, dependency-free web tool that inspects Minecraft mod `.jar` files
entirely inside the browser and reports:

- the mod loader (Forge / NeoForge / Fabric / Quilt)
- the supported Minecraft version range
- required and optional dependencies
- missing dependencies, mixed loaders and mixed game versions across a set of jars

No file ever leaves the machine — parsing is done with `DecompressionStream`
and plain JavaScript. No build step, no external scripts.

**Live:** https://mami00003.github.io/mod-dependency-checker/

Unofficial tool. Minecraft is a trademark of Mojang Synergies AB.
