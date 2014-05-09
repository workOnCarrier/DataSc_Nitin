## CRAN

## BioConductorProejct

## available.packages()
### steps follow
In R studio use the following commands
a<-available.packages()
head(rownames(a),3) ## shows the names of the first few packages
### look for Task Views link which groups together many R packages related to a given topic

## installing  new packages
install.packages("slidify") ### installs the package slidify from CRAN
install.packages(c("slidify","ggplot2","devtools")) --- using the character vector

## installing from different source
source ( "http://bioconductor.org/biocLite.R")
biocLite() -- installs multiple packages
biocLite(c("GenomicFeatures","AnnotationDbi")) -- installs specific packages


library() function loads a library
e.g. library(ggplot2) -- do not use quotes for packages name
search() -- gives the functions loaded for the package


