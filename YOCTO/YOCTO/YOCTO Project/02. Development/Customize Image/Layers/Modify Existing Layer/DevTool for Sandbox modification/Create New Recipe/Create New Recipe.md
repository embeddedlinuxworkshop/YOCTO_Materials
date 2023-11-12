


### DevTool:`Used for modifying layers in a safe-way by creating sand-box then integrating the results.`



```bash

> devtool add <github_link> # generate recipe that I can build.
> devtool edit-recipe <recipe_name> 
> devtool build <recipe_name>
> devtool deploy-target <recipe> # output image with recipe and its dependencies.


## Merging recipe to workspace.
> devtool finish -f <recipe_name> <Layer_Path>

## deleting workspace to save spaces.
> rm -rf workspace/...
```

