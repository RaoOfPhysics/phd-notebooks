# My PhD notebooks

[![Achintya's PhD repos](https://img.shields.io/badge/collection-Achintya's%20PhD%20repos-yellowgreen.svg)](https://github.com/RaoOfPhysics/phd)
![language: R](https://img.shields.io/badge/language-R-blue.svg)
![status: WIP](https://img.shields.io/badge/status-WIP-red.svg)

A collection of my PhD-related Jupyter notebooks, containing mostly WIP material, which serves as a scratchpad for my work.

## Setup information

I work mostly with [R](https://www.r-project.org/), and that's what I've used in these notebooks.

Please note that efforts to run the code in the `.ipynb` files involving the `dat` data frame **will fail**, since I cannot make the underlying research data public yet.
In particular, when the following line is called in the code, the file it refers to (`final_dataset.csv`) can only be found in my private storage space on CERN's internal servers:

```{r}
dat <- read.csv(file = "../quant_analysis/final_dataset.csv", header = TRUE)
```

However, if you want to download the notebooks and poke around, you will need to install:

- Jupyter, for opening the notebooks themselves: [http://jupyter.readthedocs.io/en/latest/install.html](http://jupyter.readthedocs.io/en/latest/install.html)
- IRkernel, for running R code in the notebooks: [https://irkernel.github.io/installation/](https://irkernel.github.io/installation/)

## Licence

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/InteractiveResource" property="dct:title" rel="dct:type">My PhD notebooks</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/RaoOfPhysics/201608_ICHEP" property="cc:attributionName" rel="cc:attributionURL">Achintya Rao</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
