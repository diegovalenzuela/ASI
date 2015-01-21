#Oyster DEG analysis

![oyster](http://www.esquire.com/cm/esquire/images/oyster-021207-460x360.jpg)

###Introduction

We are going to perform a differentially expression analysis (DEG) of oysters after a heat-shock stress.

##Downloading data

To download the data:

````
$ ./Data curl -O -k https://raw.githubusercontent.com/sr320/austral/master/modules/data/Cgigas-HS-count.txt

````

##Run DESeq2
####Insalling DESeq2 Pakage
````
%%R
# Installing DESeq2
source("http://bioconductor.org/biocLite.R")
biocLite("DESeq2")
````






