# analizadanych
```{r}
dane<-apartments_pl_2024_06
library(dplyr)
install.packages("naniar")
library(naniar)
dane_gdansk<-filter(dane, city=="gdansk")
vis_miss(dane_gdansk)
miss_var_summary(dane_gdansk)

```

