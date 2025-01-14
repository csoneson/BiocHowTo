# BiocHowTo

This repository contains short, stand-alone "How To" documents related to 
Bioconductor. 

## How to contribute

To contribute, first fork this repository and create a new branch. Then 
copy and rename the `howto_template.qmd` file (inside the `vignettes` 
directory), and edit the copy accordingly. Next, add any new package that you 
are using to the dependencies of the package, e.g. using 

```
usethis::use_package("new_dependency")
```

Then, push the changes to your forked repository and open a pull request to 
the `devel` branch of the parent repository.
