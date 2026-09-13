JVLIVS Mod - Forge 26.2 starter project
=======================================

Requirements
------------
- Windows, Linux, or macOS
- JDK 25
- Internet access on the first Gradle build

Open/import this folder as a Gradle project in IntelliJ IDEA.

Windows commands
----------------
1. Open a terminal in this project folder.
2. Run:

   gradlew.bat runClient

If the Gradle wrapper is missing, generate/download it using a compatible
Gradle installation, or copy gradlew, gradlew.bat, and the gradle/wrapper folder
from the official Forge 26.2 MDK.

Important
---------
The run/mods folder is normally empty in a Forge development environment.
The mod is loaded from the source set through the run configuration.

The mod ID must remain "jvlivsmod" in:
- ExampleMod.java
- mods.toml
- build.gradle run configuration
