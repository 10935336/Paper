A PaperMC fork that delete sand duper fix.
===========

**you can enable TNT, Rails and Carpet duping by config, but you can't enable sand duping, so this is the fork that you can use sand duping.**


**Since my workflow has been separated from github, I will not update this repository, but I will release the build in release.**

Please note that this repository cannot be directly compiled correctly.



**The following is the original description, download addresses, etc. are not used**



一个删除了刷沙机修复补丁的 PaperMC
===========

**你可以在设置中启用 TNT、铁轨和地毯复制，但刷沙机却不行，所以这是一个可以让你使用刷沙机的 PaperMC fork。**

本仓库未更新，请直接在 Release 下载构建。












Paper [![Build Status](https://papermc.io/ci/job/Paper-1.16/badge/icon)](https://papermc.io/ci/job/Paper-1.16/)
===========

High performance Spigot fork that aims to fix gameplay and mechanics inconsistencies.


**Support and Project Discussion:**
 - [IRC](https://irc.spi.gt/iris/?channels=paper) or [Discord](https://discord.gg/papermc)


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
    <version>1.16.2-R0.1-SNAPSHOT</version>
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
    compileOnly 'com.destroystokyo.paper:paper-api:1.16.2-R0.1-SNAPSHOT'
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
