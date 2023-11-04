

```
For creating image that is to be shared with other developers.
```



## Actions


1. Get list of all image recipes exists

```bash
 ls meta*/recipes*/images/*.bb
```



```bash
# *.bb
IMAGE_INSTALL += " strace" # add strace package on image.
```

---

```bitbake

bitbake <image-recipe-name>

```
