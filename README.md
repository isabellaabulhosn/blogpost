# Most Useful Libraries in R

_Some of the most useful libraries you should download in R and a brief overview of what they do_

### How to Install a Package

```
install.packages("[package]")  
library("[package]")
```

### Data Manipulation 

#### dplyr 
This is one of the most useful packages I used. It is absolutely necessary for data manipulation. You need it to filter data tables, add columns, choose specific columns, and joining datasets.   
You can find a link to dplyr's (and tidyr's) cheatsheet [here](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf).

#### tidyr
This package is also useful in data manipulation. It often goes hand in hand with dplyr.

#### stringr 
This is necessary to have when working with character strings in data. You can use this package to convert and manipulate character strings which can be necessary for some datasets.

#### lubridate 
You cannot work with data that has dates without this package. It converts dates as numbers into dates that R recognizes as dates. It is beneficial when making visualizations like time plots that use dates on an axis. It also applies to working with times.    
You can find a link to lubridate's cheatsheet [here](https://rawgit.com/rstudio/cheatsheets/master/lubridate.pdf).


### Data Visualization 

#### ggplot2 
This is one of the most popular packages for creating visualizations. I made almost all of my graphs with ggplot. You can make a variation of visualizations, from scatterplots and maps to histograms and more.    
You can find a link to ggplot2's cheatsheet [here](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf).


### Data Presentation 

#### shiny 
This is one of the most useful tools in creating a means to present results. You can make interactive visualizations that react to user input. You can also publish your web apps online.    
You can find a link to shiny's cheatsheet [here](https://shiny.rstudio.com/images/shiny-cheatsheet.pdf).


### Other Libraries I Found Useful 

#### openintro
I used this package to convert state names to abbreviations, which was necessary in joining some of my datasets. You can use commands like:   
```
state2abbrv
```