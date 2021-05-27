# LoCCAM Public Repository


## How to import LoCCAM?
#### 1. Include in the `gradle.project`'s `repositories` section:

```maven { url "https://jitpack.io" }```

Example:
```
allprojects {
    repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
```

#### 2. Include in the `gradle.app`'s `dependencies` section:

```implementation 'com.github.makleyston-ufc.PMS:pms:v0.3'```

Example:
```
dependencies {
    ...
    implementation 'com.github.great-ufc:loccam:0.0.2'
}

```
