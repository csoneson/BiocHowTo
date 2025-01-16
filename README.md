# BiocHowTo

This repository contains short, stand-alone "How To" documents related to 
Bioconductor. 

## How to contribute

1. Fork this repository and create a new branch. 
2. Copy and rename the `howto_template.qmd` file (inside the `vignettes` 
directory), and edit the copy accordingly. Please choose the name for the new 
vignette in such a way that it is unique and clearly indicates the content. 
Note that the title of the vignette should be added both to the `title` field 
and the `%\VignetteIndexEntry` in the YAML section.
3. Test the vignette locally in a fresh R session, to make sure that it is 
self-contained and runs without errors.
4. Add your name to the `Author` list in the `DESCRIPTION` file.
5. Add any new package that you are using to the list of dependencies of the 
package, e.g. using

```
usethis::use_package("new_dependency")
```

6. Push the changes to your forked repository and open a pull request to 
the `devel` branch of the parent repository.

## How to suggest a new topic

To suggest a new topic for a HowTo, open an issue and provide some more
details of your suggestion. 
