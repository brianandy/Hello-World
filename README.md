```{r}
library(survey)
library(tidyverse)
library(foreign)
library(ggthemes)
setwd("C:/Users/Brian Andrew/Desktop/Data Science/brianandrew/csv")
tsetse <- read.spss(file.choose(), to.data.frame = T)
```
