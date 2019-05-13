---
title: "SciViews::R"
date: 2019-05-05T12:15:35+01:00
image: images/software/sciviews-r.png
bgImage: images/background/page-title.jpg
icon: ti-bar-chart
downloadTitle: 'Download SciViews'
downloadLabel: 'github.com/SciViews/SciViews'
downloadURL: 'https://github.com/SciViews/SciViews'
linkTitle1: 'data.io'
linkLabel1: 'github.com/SciViews/data.io'
linkURL1: 'https://github.com/SciViews/data.io'
linkTitle2: 'chart'
linkLabel2: 'github.com/SciViews/chart'
linkURL2: 'https://github.com/SciViews/chart'
linkTitle3: 'flow'
linkLabel3: 'github.com/SciViews/flow'
linkURL3: 'https://github.com/SciViews/flow'
type : software
author: Philippe Grosjean
categories: 
  - "Software"
tags:
  - "R"
  - "Tidyverse"
---

### An extension to the Tidyverse

SciViews::R is an extension to the [Tidyverse](https://www.tidyverse.org/) aiming to make [R](https://www.r-project.org/) even more easy to use by everyone. The various packages that compose the SciViews::R dialect offer a coherent set of fonctions to import, manipulated, plot and analyze data. It is basically a slightly modified Tidyverse, with more emphasis on formulas and coherence of its interface.

Main packages are:

1. **data.io**, an enhanced data import/export with metadata (labels, units, ...). It also allow to "decorate" standard datasets with such metadata, in various languages.
2. **chart**, a package dedidated to plots with an emphasis on the formula interface for ggplot2. It also creates plots that can be easily combined (compatibility) from the three main R plotting engine: base plots, lattice and ggplot2.
3. **flow** proposes two alternate pipe operators that are easier to use that the magrittr'one in Tidyverse. One of theses pipes operators (`%>_%`) also make tidyeval easier.


#### Example

```r
# Load SciViews::R
SciViews::R
```

