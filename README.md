---
title: "Notes"
author: "Ville Inkinen"
date: "June 09, 2023"
output:
  html_document:
    keep_md: true
    warning: false
knitr:
    warning: FALSE
---

### Exploration of Mapbiomas de- and reforestation patterns in San José de Chiquitos


Forest vs non-forest in 1994. Property bounadries in white.

![](index_files/figure-html/unnamed-chunk-1-1.png)<!-- -->

Land cover change 1995-2015 outside properties and within properties

![](index_files/figure-html/unnamed-chunk-2-1.png)<!-- -->


Deforestation and reforestation over 1995-2015. Defined as 5 consequtive years of forest/non-forest in 1990-1994 and 2016-2020

![](index_files/figure-html/unnamed-chunk-3-1.png)<!-- -->

Deforestation and reforestation over 1995-2015. No requirement of stable land cover before and after.

![](index_files/figure-html/unnamed-chunk-4-1.png)<!-- -->

While the patterns are preserved, the differences are not marginal:

![](index_files/figure-html/unnamed-chunk-5-1.png)<!-- -->

Baseline and endline land cover categories for re- and deforestation:

![](index_files/figure-html/unnamed-chunk-6-1.png)<!-- -->


![](index_files/figure-html/unnamed-chunk-7-1.png)<!-- -->

Notes:

- Most reforestation came from the category "Other non-forest natural formation" (13).
- Most deforestation came from pasture + agriculture. "Other non-forest" still a significant contributor.

Reforestation pixels, land use in 1985:

![](index_files/figure-html/unnamed-chunk-8-1.png)<!-- -->

Questions:

- Is other non-forest a residual category?
  - Prediction error high -> "other" vs. separately trained and classified "other"
- Misclassification between other non-forest and grassland, pasture, and agriculture?
