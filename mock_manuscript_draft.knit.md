---
title: "Mock Manuscript"
author: "xinyue"
date: "2026-02-13"
output:
  pdf_document: default
  html_document: default
---



## Data



In this manuscript I have created tables and graphs to compair skull sizes between male and female grizzly bears in BC. this was downloaded from the data "Compulsory Inspection Data 1900 to 2023-24" from the British Columbia database, linked in the reference.



The original data becomes filtered to include only Grizzly Bear related data, which will be the data set used for the following graphs and tables.







Here is a Skim overview of the Grizzly Bears Data.


Table: Data summary

|                         |           |
|:------------------------|:----------|
|Name                     |Piped data |
|Number of rows           |9843       |
|Number of columns        |18         |
|_______________________  |           |
|Column type frequency:   |           |
|character                |10         |
|numeric                  |8          |
|________________________ |           |
|Group variables          |None       |


**Variable type: character**

|skim_variable   | n_missing| complete_rate| min| max| empty| n_unique| whitespace|
|:---------------|---------:|-------------:|---:|---:|-----:|--------:|----------:|
|CID             |         0|          1.00|   6|   6|     0|     9843|          0|
|Species         |         0|          1.00|   4|   4|     0|        1|          0|
|Kill Type       |         0|          1.00|   7|  12|     0|        5|          0|
|Sex             |         0|          1.00|   1|   1|     0|        3|          0|
|Sub Region      |         0|          1.00|   1|   1|     0|        3|          0|
|LEH Hunt Area   |      6094|          0.38|   3|   4|     0|      188|          0|
|Skull Type      |         0|          1.00|   1|   1|     0|        4|          0|
|Tooth Code      |      1014|          0.90|   1|   1|     0|        3|          0|
|Wear/Stain Code |      9390|          0.05|   1|   1|     0|        1|          0|
|Other Code      |      9352|          0.05|   1|   1|     0|        2|          0|


**Variable type: numeric**

|skim_variable  | n_missing| complete_rate|        mean|        sd|       p0|      p25|        p50|         p75|     p100|
|:--------------|---------:|-------------:|-----------:|---------:|--------:|--------:|----------:|-----------:|--------:|
|Kill Date      |         0|          1.00| 19963350.85| 125997.84| 19750401| 19850916| 19960501.0| 20080523.50| 20210910|
|Region         |         0|          1.00|        6.04|      1.30|        1|        6|        6.0|        7.00|        9|
|WMU            |         0|          1.00|      630.40|    134.71|      114|      604|      629.0|      738.00|      900|
|Skull Length   |         0|          1.00|      336.85|     38.95|       21|      311|      334.0|      362.00|      750|
|Skull Width    |         0|          1.00|      191.05|     29.99|       18|      170|      187.0|      211.00|      426|
|Tooth Age      |      1001|          0.90|        7.88|      5.61|        1|        4|        6.0|       11.00|       99|
|Wear/Stain Age |      9390|          0.05|        8.38|     12.81|        1|        4|        6.0|        8.00|       99|
|Other Age      |      9793|          0.01|       13.58|     22.47|        1|        3|        4.5|        8.75|       99|

Here is a comparison of two scatter plot of Grizzly Bear skull size by sexes, this data shows only the skulls reported in Region 4, which represents bears found in the Kootenay Area of British Columbia, Canada.

![Grizzly Skulls Comparison of Bears found in Kootenay Area from 1900-2023. Female bears n=3280, Male bears n=6489. Excluding from Dataset bear skulls catagorized as U=Unknown. In Females Mean Length=319mm, Mean Width=179mm. In Males Mean Length=346mm, Mean Width=197mm. Male Grizzly skulls on average are larger than females in both length and width.](mock_manuscript_draft_files/figure-latex/graphs-1.pdf) 





## Article

[@fu2024]

[@hacioglu2024]

[@compulso]

[@forests]

## References

::: {#refs}
:::
