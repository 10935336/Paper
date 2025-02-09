**No update plan at the moment.**

Maybe try

https://github.com/neko-craft/NekoAgent

https://github.com/MrTransistorsChannel/SandDupe

https://github.com/Nats-ji/paper-sand-dupe-unpatched


<br/>
<br/>
<br/>
<br/>
<br/>

A PaperMC fork that delete sand duping fix
===========
**You can enable TNT, Rails and Carpet duping by config, but you can't enable sand duping, so this is the fork that you can use sand dupers.**

**Just delete Fix-sand-dumping.patch, no other changes.** 

Please download directly in "Releases".

**the version number and code are consistent with Paper ci server.**

For example, the version #496 you downloaded from the Paper ci server is basically the same as the version #496 downloaded from this repository, except that there is no Fix-sand-dumping.patch.

Please note that since my workflow does not depend on this repository, so this repository has not been updated and cannot be compiled correctly.

<br/>

一个删除了刷沙修复补丁的 PaperMC fork
===========
**你可以在配置文件中启用刷TNT、刷铁轨、刷地毯，但是你无法在配置文件中启用刷沙，所以这是一个可以让你用刷沙机的 fork。**

**仅删除 Fix-sand-dumping.patch，未做其他改动。**

请直接在 Releases 中下载构建。

**版本号与 Paper ci 服务器一致。**

也就是说，你在 Paper ci 服务器下载到的 #496 版本和本仓库的 #496 版本是基本上一样的，只不过这里的版本没有 Fix-sand-dumping.patch。

请注意，由于我的工作流程不依赖于此存储库，因此该存储库未更新，且无法正确编译。

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

Paper [![Build Status](https://papermc.io/ci/job/Paper-1.16/badge/icon)](https://papermc.io/ci/job/Paper-1.16/)
===========

High performance Spigot fork that aims to fix gameplay and mechanics inconsistencies.


**Support and Project Discussion:**
 - [IRC](https://webchat.esper.net/?channels=paper) or [Discord](https://discord.gg/papermc)


How To (Server Admins)
------
Paperclip is a jar file that you can download and run just like a normal jar file.

Download Paper from our [downloads page](https://papermc.io/downloads).

Run the Paperclip jar directly from your server. Just like old times

  * Documentation on using Paper: [paper.readthedocs.io](https://paper.readthedocs.io/)
  * For a sneak peak on upcoming features, [see here](https://github.com/PaperMC/Paper/projects)

How To (Plugin Developers)
------
 * See our API patches [here](Spigot-API-Patches)
 * See upcoming, pending, and recently added API [here](https://github.com/PaperMC/Paper/projects/6)
 * Paper API javadocs here: [papermc.io/javadocs](https://papermc.io/javadocs/)
 * Maven Repo (for paper-api):
```xml
<repository>
    <id>papermc</id>
    <url>https://papermc.io/repo/repository/maven-public/</url>
</repository>
```
 * Artifact Information:
```xml
<dependency>
    <groupId>com.destroystokyo.paper</groupId>
    <artifactId>paper-api</artifactId>
    <version>1.16.4-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
 ```

**Or alternatively, with Gradle:**

 * Repository:
```groovy
repositories {
    maven {
        url 'https://papermc.io/repo/repository/maven-public/'
    }
}
```
 * Artifact:
```groovy
dependencies {
    compileOnly 'com.destroystokyo.paper:paper-api:1.16.4-R0.1-SNAPSHOT'
}
```

How To (Compiling Jar From Source)
------
To compile Paper, you need JDK 8, maven, and an internet connection.

Clone this repo, run `./paper jar` from *bash*, get files.

How To (Pull Request)
------
See [Contributing](CONTRIBUTING.md)

Special Thanks To:
-------------

![YourKit-Logo](https://www.yourkit.com/images/yklogo.png)

[YourKit](https://www.yourkit.com/), makers of the outstanding java profiler, support open source projects of all kinds with their full featured [Java](https://www.yourkit.com/java/profiler/index.jsp) and [.NET](https://www.yourkit.com/.net/profiler/index.jsp) application profilers. We thank them for granting Paper an OSS license so that we can make our software the best it can be.
