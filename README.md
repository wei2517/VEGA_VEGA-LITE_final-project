# Vega

Use [*Vega*](https://vega.github.io/vega/) to make a statistic map and plots.

## Motivation
For my final project, i choose *Vega* and *Vega-lite*, a free,statistical, and visualized software to learn. Because of the another class, i met Yintong community, i want to make a map connected to it.  Besides, I also want o use VEGA-LITE to make some visual description for my own project in BME. Without doubt, a visualization grammar is also an useful tool  to make the unified graphics.

## Feature
* Data visualization.
* A declarative language for describing visualizations.
( include the data transformations and visual encoding rules needed to express a rich space of visualizations. )
* A convenient means for writing programs that generate visualizations, ranging from interactive design tools to automatic chart recommendation tools. 

## VEGA VS VEGA-LITE?
* VEGA: A visualization grammar, a declarative language for creating, saving, and sharing interactive visualization designs.
* VEGA-LITE: Vega-Lite is a high-level grammar of interactive graphics. It provides a concise JSON syntax for rapidly generating visualizations to support analysis. 

## Example
### Connected Scatter Plot
![](https://i.imgur.com/6kDirI5.png)

![](https://i.imgur.com/OmJhkND.png)


## Purpose
1. Draw a map around Yintong community.
2. Use VEGA-LITE to make the plots that connect to my own project in BME.

## Process
### Map:
1. Put the raw data of West Central Dist., Tainan City into VEGA-LITE.(https://raw.githubusercontent.com/jason2506/Taiwan.TopoJSON/master/topojson/villages/villages-67000370.json)
2. Use VEGA-LITE program to change the feature that you want.
3. Use [*Vega-Lite Block*](http://blockbuilder.org/) to embed the figure to the web.
4. Achievement: (https://bl.ocks.org/wei2517/raw/50f0c2bbf8420009a470fb0500a5a79f/20b5436a06f5f20ebc255619d3298faffbf1e897/)
5. Because there is no raw data for the name of the villages, I use "小畫家" to key the name on the map(.png):
![](https://github.com/wei2517/VEGA_VEGA-LITE_final-project/blob/master/West%20Central%20Dist.%2C%20Tainan%20City..png)

### Other plots: (There are also some introduction of the figure in the web)
1. The correlation between the vascular age predicted from PPG signal and the real age:
(https://bl.ocks.org/wei2517/raw/c758304baca44c53a8c988acc0919d7d/6d20759c015682d1c86aec5163f4f186aea52933/)
(png.):
![](https://github.com/wei2517/VEGA_VEGA-LITE_final-project/blob/master/The%20correlation%20between%20the%20vascular%20age%20predicted%20from%20PPG%20signal%20and%20the%20real%20age.png)
2. The correlation between subjects number and age:
(https://bl.ocks.org/wei2517/raw/a618af305df39692426f1b1c5cd377f4/f980a82e1111071db4ed16cd58bcfe7a1fb5b942/)
(png.):
![](https://github.com/wei2517/VEGA_VEGA-LITE_final-project/blob/master/The%20correlation%20between%20subjects%20number%20and%20age.png)
3. PPG signal:
(https://bl.ocks.org/wei2517/raw/568b3dfaa4a6b50c741ac7f4fe848afb/4c0a5dda93acfc966e4e7a770503118c04415d33/)
(png.):
![](https://github.com/wei2517/VEGA_VEGA-LITE_final-project/blob/master/PPG%20signal.png)
* Under the web you can also see the links that can help you th export the figure to the type you want!

## Summary
VEGA/VEGA-LITE can be an one of choice for you to make figures,however, you have to spend some time learning the documents. Besides, it also let us to embed our figures to the wed easily and conveniently.
