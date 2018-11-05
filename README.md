# CrossoverDesign: Constructing efficient crossover designs with possible subject dropout mechanism


### Introduction

The crossover models and interference models are frequently used in clinical trials, agriculture studies, social studies, etc. While some theoretical optimality results are available, it is still challenging to apply these results in practice, especially under the varieties of drop-out mechanism. The available theoretical results, due to the complexity of exact optimal designs, typically require some specific combinations of sample size, number of treatments, and number of periods. In addition, those results are generally for some selected design problems and specific drop-out mechanism. These obstacles make the application of the theoretical results rather difficult. This R-package address these issues through a new algorithm method, based on a revision of optimal weight exchange algorithm Yang et al. (2013) <doi:10.1080/01621459.2013.806268>. It provides efficient crossover designs quickly under varieties situations, for different optimality criterion, different parameter of interest, different numbers of treatments and periods, regardless number of sample size and dropout mechanism. The lower bound of relative efficiency is provided as well.


### Usage
- To install the package, 
```r
install.packages("CrossoverDesign")
```

- To construct design, one can either use `design` function or use the shiny app. To launch the app,
```r
CrossoverDesign::design_app()
```






