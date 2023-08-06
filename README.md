<div align="center">

  <h1>Maven Repository</h1>
  <p>Upload the CutePixels project</p>
  
</div>

## How to use
Maven include this:
```xml
<repositories>
  <repository>
    <id>cutepixels-maven</id>
    <name>CutePixels Maven</name>
    <url>https://raw.github.com/CutePixels/mvn-repo/main</url>
  </repository>
</repositories>
```
Gradle(Groovy DSL) include this:
```groovy
repositories {
  maven {
          name = "CutePixels maven"
          url = 'https://raw.github.com/CutePixels/mvn-repo/main'
  }
}
```
Gradle(Kotlin DSL) include this:
```kotlin
repositories {
  maven {
          name = "CutePixels maven"
          url = uri('https://raw.github.com/CutePixels/mvn-repo/main')
  }
}
```
If you are in China and cannot connect GitHub, you can replace the `github.com` to `kgithub.com` or `hub.fgit.ml`.
