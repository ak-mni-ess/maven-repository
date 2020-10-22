# Maven Repository

The [GitHub Pages](https://emoto-kc-ak.github.io/maven-repository) of this repository serves as a maven repository for custom libraries.

## Gradle

To resolve a library in this repository, add the following lines to your `build.gradle`.

```
repositories {
    maven {
        url 'https://emoto-kc-ak.github.io/maven-repository'
    }
}
```

## Publishing a library

Copy the library you want to publish into the [docs](./docs) directory.