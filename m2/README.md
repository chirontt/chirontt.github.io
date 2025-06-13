# Maven artifact repo

Online Maven repository, comprised of `Linux riscv64`, `Windows on Arm64` and `FreeBSD aarch64/x86_64` artifacts,
built from the following projects:

 - my [fork](https://github.com/chirontt/javafx-gradle-plugin) of the [JavaFX Gradle Plugin](https://github.com/openjfx/javafx-gradle-plugin)
 - my [fork](https://github.com/chirontt/openjdk-jfx) of the [OpenJFX (or JavaFX)](https://github.com/openjdk/jfx).

To use this Maven repo, add the following to the `pom.xml` file:
```
    <repositories>
        <repository>
            <id>chirontt-maven</id>
            <name>JavaFX Maven Repo for Linux riscv64, Windows on Arm64 and FreeBSD aarch64/x86_64</name>
            <url>https://chirontt.github.io/m2</url>
        </repository>
    </repositories>
```
