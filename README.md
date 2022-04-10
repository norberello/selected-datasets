# selected-datasets
<p align="center">

<a href="https://github.com/norberello/selected-datasets/tree/main/files">
         <img alt="Qries" src="opendoor.jpg"
         width=500">
      </a>
</p>

Some selected datasets in CSV format

datasets are in the folder `files`

To choose what to read:
`data <- read.csv(file.choose(), header = T)`

or

```
everest.deaths<-read.csv("https://raw.githubusercontent.com/norberello/selected-datasets/main/files/everestdeaths.csv")`
head(everest.deaths)
```

or for a particular dataset within a library:

```
data("Boston", package = "MASS")
```
                                                                                                                      
links to some interesting dataset sites

<https://www.rdocumentation.org/packages/openintro/versions/2.0.0>
 
<https://rdrr.io/cran/UsingR/>

<https://openpsychometrics.org/_rawdata/>

<https://guides.library.ucla.edu/psychology/data>

<https://www.discoveringstatistics.com/repository/fieldgillett/how_to_do_a_meta_analysis.html>https://cran.r-project.org/web/packages/MASS/MASS.pdf>
                               
<http://users.stat.ufl.edu/~winner/datasets.html>
                               
<https://corgis-edu.github.io/corgis/csv/?>
                               
<https://www.kaggle.com>
   
```                              
library(FactoMineR)#check data here
data(decathlon)
```
                                                                                                                      
```
library(HistData)
```
                               
                               
