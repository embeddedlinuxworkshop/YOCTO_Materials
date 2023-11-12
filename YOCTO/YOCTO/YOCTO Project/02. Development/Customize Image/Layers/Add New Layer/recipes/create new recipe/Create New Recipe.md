


> There are two methods for creating a new recipe.



1. Using `recipetool` 
```bash
recipetool create -o <recipe_name>.bb https://github.com/example/myproject.git
```
2. Manual
```bash
touch <recipe_name>.bb # new recipe file.
```



---


## Checking that recipe is added.

```bash
bitbake-layers show-recipes <layer_name>
```



---


Go to  :BoBxsRightArrowCircle:  [[Add Tasks]]


---
