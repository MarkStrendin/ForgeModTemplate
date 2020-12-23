# What is this
This is an adaptation of the Forge MDK example mod. I initially ran into a lot of issues getting the example mod working, so this repository represents my own tweaks to it to make it work the way I want it to.

# What Forge version is this for

As of the last time I updated this file, this template mod should work for Forge version `1.16.4-35.1.4`.

# How to modify this into your own mod

1. Find and rename all instances of `marktemplatemod` and `MarkTemplateMod` to something relevant to your own mod.
2. Re-home the now renamed `MarkTemplateMod.jar` to a more appropriate folder now that your mod is not called MarkTemplateMod.
3. Customize `build.gradle` and `.\src\main\resources\pack.mcmeta` and `.\src\main\resources\META-INF\mods.toml` for your own mod.
4. Start replacing the example code with your own.

# How to build

In the root folder for this repository run `.\gradlew.bat build`.

# How to run

`.\gradlew.bat runClient`

# Where to find the jar file

Doing a "build" (see above) will create a .jar file for your mod in the `.\build\libs\` folder.