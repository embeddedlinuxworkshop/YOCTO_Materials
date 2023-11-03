

## PATH

```
<your directory>/poky/build/conf
```

---

## Most Commonly used Configuration.

```bash

INHERIT += "rm_work" # remove work directory after each recipe compilation to reduce disk usage.


IMAGE_INSTALL_append = " strace helloworld" # add extra packages on your image for development.

EXTRA_IMAGE_FEATURES # Image Features `Sweeping changes`.

```

