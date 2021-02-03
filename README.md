# R-reactable

The R Markdown file includes some work with the package `reactable`. The initial elements of the work are taken from:
https://towardsdatascience.com/recreate-publication-quality-interactive-tables-in-r-using-reactable-187407bc9702

However, I have extended the analysis to produce the following table showing COVID deaths and excess deaths via sparklines, as well as a rate per 100,000 field formatted via CSS. The table is interactive when rendered as html.

![Sparkline Table](https://github.com/Ya5s3r/R-reactable/blob/main/COVID-Excess-Deaths-Final_files/figure-html/country_table_sparklines.png)

And also the following heat maps using `ggplot2`, showing the % deviation from expected deaths. Firstly by country and then by UK region.

![Heat Map](https://github.com/Ya5s3r/R-reactable/blob/main/COVID-Excess-Deaths-Final_files/figure-html/excess-deaths-country-v2.png)

![Heat Map](https://github.com/Ya5s3r/R-reactable/blob/main/COVID-Excess-Deaths-Final_files/figure-html/excess-deaths-uk.png)

