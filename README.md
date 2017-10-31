# R data analysis & visualization for beginners
A tutorial of the basics of data analysis and visualization in the R programming language, no experience with R or coding required!

Here's how to get started:

- If you don't have R installed, [install it](https://cran.r-project.org).
- If you don't have RStudio installed, [install it](https://www.rstudio.com/products/rstudio/download/#download).
- Download the raw data for this project by right-clicking and downloading [this](https://raw.githubusercontent.com/dhmontgomery/r-data-for-beginners/master/speedingdata.csv).
- Open RStudio and enter the following code in the app's Console (the panel on the left side of the window, at the `>` symbol) to install necessary packages:

```
install.packages(c("tidyverse", "lubridate", "scales"))
```

- Set your "working directory" in RStudio to the location of `speedingdata.csv`, the data you downloaded. You can do this by clicking the Session Menu > Set Working Directory > Choose Directory and then navigating to the folder where the data is.

Once you've done that, you're ready to start the lesson in [`r-for-beginners.md`](https://github.com/dhmontgomery/r-data-for-beginners/blob/master/r_for_beginners.md)!
