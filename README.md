# EDA-Fall2023
ENV872 - Environmental Data Exploration - Fall 2023
Lab - Monday at 3:05
```{r}
recipe3 <- function(x, f){
  mix1 <- x*f
  mix2 <- x/f
  return (list(mix1 = mix1,
+     mix2 = mix2))
}
