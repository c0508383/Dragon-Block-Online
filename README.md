## Welcome to the Dragon Block Online Repository.
![](images/logo.png)  

> Dragon Block Online is a [Minecraft](https://minecraft.net/) mod based on the popular anime series "Dragon Ball", created by Akira Toriyama. It is currently being developed with a heavy focus on customizability and RPG mechanics, with Dragon Ball elements on top of a solid core system.
The mod is made for Minecraft Forge **1.7.10** in collaboration with KAMKEEL's CustomNPC+ mod, with the mod being used as a dependency.

Support us on Ko-Fi!

<a href="https://ko-fi.com/louisxiv"> <img src="https://i.imgur.com/EvkTjYS.png" alt="Support Me!"  width="180" height="180"> </a>
<a href="https://ko-fi.com/kamkeel"> <img src="https://i.imgur.com/kNVNa1M.png" alt="Support KAM!"  width="180" height="180"> </a>

### ❗ Notice
The following is a fan-based MINECRAFT MOD. Dragon Ball, Dragon Ball Z, Dragon Ball GT, and Dragon Ball Super are all owned by Funimation, Toei Animation, Shueisha and Akira Toriyama. Please support the official release.

### 🔹 Installation
This mod uses CustomNPC+ as a dependency, and thus must be installed alongside this mod. Report any bugs if found, thank you and enjoy.

## Cloning / Compiling / Building

git clone call `git submodule update --init --recursive`

Using IntelliJ, take the following steps: 
1. Run `setupDecompWorkspace` under the `forgegradle` tab.
2. Refresh Gradle.
3. Run `genIntellijRuns` under the `other` tab to set up your Minecraft runs.

or for Eclipse, run `gradlew setupDecompWorkspace eclipse` then import the project. 

Mixin code will not work if you do not add `--tweakClass org.spongepowered.asm.launch.MixinTweaker --mixin customnpcs.mixins.json` to your program arguments.
