# All Spigot NMS
All NMS versions of spigot in one jar file. How awesome is that?

![Build Test](https://github.com/Jacxk/all-spigot-nms/workflows/Build%20Test/badge.svg)

# Usage
To use this tool you have to follow the steps bellow:
* Clone this repository: `git clone https://github.com/Jacxk/all-spigot-nms`
* Open a terminal inside the repository folder:
  * Enter bash folder: `cd src/`
  * Run the tool: `bash ./run.sh`
  * Choose `All of the above` to get the jar file
* Import the compiled jar file into your IDE
* Start coding...

# Importing
### Maven:
```xml
<dependency>
    <groupId>local.spigot.nms</groupId>
    <artifactId>AllSpigotNMS</artifactId>
    <version>LATEST</version>
    <scope>system</scope>
    <systemPath>${project.basedir}/PATH TO FILE HERE</systemPath>
</dependency>
```
### Gradle:
```groovy
dependencies {
    implementation(files("/path/to/file.jar"))
}
```

#
All the NMS version. [click here](/spigot_versions)\
Description on compiling the Jar file. [click here](/src)

*I'm not distributing anything, please don't sue me Mojang.*
