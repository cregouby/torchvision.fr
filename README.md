# torchvision.fr <img src='images/logo-fr.png' align="right" style="width: 15%"/>

<!-- badges: start -->

<!-- badges: end -->

Le paquet d'internationalisation de **{torchvision}** en français (fr_FR)

## Installation

Vous pouvez installer la version de development de **{torchvision.fr}** depuis [GitHub](https://github.com/) via:

``` r
# install.packages("pak")
pak::pak("cregouby/torchvision.fr")
```

## Exemple

Voici comment utiliser {torchvision} avec l'aide en français :

``` r
# configure la session en langue française
Sys.setenv(LANGUAGE = "fr")

# charge la librairie torchvision en traduction française et {torchvision}
library(torchvision.fr)
library(torchvision)

# consulte l'aide normalement
?transform_affine
```

![exemple de page de documentation en français dans l'onglet Help de RStudio](images/clipboard-2721924466.png)
