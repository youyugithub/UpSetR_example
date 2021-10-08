# UpSetR_example

```
library(UpSetR)

listInput <- list(
  one = rpois(30,100), 
  two = sample(1:100,20), 
  three = sample(1:100,25),
  four = rbinom(40,100,0.5))
upset(fromList(listInput), order.by = "freq")
```
