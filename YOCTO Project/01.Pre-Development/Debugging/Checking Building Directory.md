


---
## Objectives:

1. Understanding Building directory.
2. Understanding its contents.
3. Overview #bitbake Main Operations on #build_directory
---

### 1. Understanding Building directory.
---
![[Screenshot 2023-11-03 at 5.01.14 AM.png]]


---

#### <mark style="background: #ADCCFFA6;">a. conf</mark>

###### 1. Contains: `contains configuration file to control Poky and Bitbake.`
##### 2.files:
1. `build/conf/local.conf`
2. `build/conf/bblayers.conf`

#### <mark style="background: #ADCCFFA6;">b. downloads</mark>

1. this stores all downloaded artifacts, acts as cache.

#### <mark style="background: #ADCCFFA6;">c. shared state cache</mark>

1. cache mainly used to speed up the future build process. 
#### <mark style="background: #ADCCFFA6;">d. tmp</mark>

![[Screenshot 2023-11-03 at 5.36.51 AM.png]]
#### Contains:
---

1. deploy directory.

```
$ Contains final output ---> 
a. Images.
b. rootfs.
c. bootloader.
```

2. sysroots-components ---> `collection for all sysroots`
3. sysroots-uninative ---> `used when native utilities are generated.`
4. work #debugging
```
> Used for debugging purpose.
> Directory Name:
> <AR>/<name>/<version>
> to be continued for debugging.
```
##### For each recipe <<mark style="background: #FFF3A3A6;">ARCH/NAME/VERSION</mark>> Contains: 
1. `sysroot` ---> Target.
2. `sysroot-native` ---> Native.
3. `Image` ----> This contains the files installed by the recipe.
4. `temp` ----> This stores Bitbake's task code and execution logs.

---

>  📝 When we see a missing header or a link failure, we must double-check whether our **sys-root** directory (target and host) contents are correct.

5. work-shared.
