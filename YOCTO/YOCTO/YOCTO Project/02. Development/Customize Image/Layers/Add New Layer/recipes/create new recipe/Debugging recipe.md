

```bash


# method 1
bitbake -c devshell <recipe name>

# method 2
# reading task log /tmp/work/....



# method 3 
bitbake -v <recipe name> # checking dependencies.


# method 4
bitbake -g <recipe name> -u taskexp # checking dependencies.




# method 5
bitbake-layers show-recipes 



# method 6
bitbake -c listtasks <recipe name>

```

