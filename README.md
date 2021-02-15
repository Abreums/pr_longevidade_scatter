Longevidade nos municípios do PR
================
Marcos Abreu

## Um exercício de “data wrangling”

Um dos meus livros prediletos sobre R é o
[ModernDive](https://moderndive.com). É muito agradável de ler, e a
estrutura de tópicos me parecer ser a melhor forma já proposta para
apresentar os diversos temas cobertos pelo livro.

Logo no início nos deparamos com uma ótima introdução sobre tipos de
gráficos e com o belo gráfico da
[figura 2.1](https://moderndive.com/2-viz.html#fig:gapminder) que mostra
a relação entre PIB e expectativa de vida entre países.

Este exercício se propõe a repetir o mesmo gráfico, porém para os
municípios do Paraná, usando as regiões para o código de cores.

## Fontes de dados

O primeiro desafio do exercício foi obter os dados necessários para o
gráfico. São eles:

  - Relação de municípios por regiões do estado;

  - População dos municípios;

  - PIB dos municípios;

  - Expectativa de vida dos municípios.

<!-- end list -->

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](readme_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
