

![Mixin Logo](docs/javadoc/resources/logo.png?raw=true)

**Mixin** is a trait/mixin framework for Java using [ASM](https://asm.ow2.io/)
and hooking into the runtime classloading process via a set of pluggable
built-in or user-provided services. Built-in services currently support Mojang's
[LegacyLauncher](https://github.com/Mojang/LegacyLauncher) system, though this
is deprecated in favour of [ModLauncher](https://github.com/cpw/modlauncher) by
cpw, which has greater extensibility and has support for Java 8 and later.

### Documentation

The main documentation for **Mixin** can be found in the
[Wiki](https://github.com/SpongePowered/Mixin/wiki).

Additional documentation for individual features and annotations can be found in
the extensive [Javadoc](http://jenkins.liteloader.com/job/Mixin/javadoc/). For
additional help use the channel [`#mixin` on the Sponge Discord Server](https://discord.gg/tBcwxz2).

### flint-mixin

Modify the source code using mixin, and add the Java 22 to 25 version to the project configuration file.

Source code of the https://github.com/SpongePowered/Mixin/