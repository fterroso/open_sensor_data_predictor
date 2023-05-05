# Human Mobility Predictor based on Open Human Flows and Traffic Data

This repository comprises the source code of the framework described in the manuscript *Human Mobility Prediction with Region-based Flows and Road Traffic Data* published in The Journal of Universe Computer Science (J.UCS). The article is available [here](https://lib.jucs.org/article/94514/).

## Abstract
Predicting human mobility is a key element in the development of intelligent transport systems. Current digital technologies enable capturing a wealth of data on mobility flows between geographic areas, which are then used to train machine learning models to predict these flows. However, most works have only considered a single data source for building these models or different sources but covering the same spatial area. In this paper we propose to augment a macro open-data mobility study based on cellular phones with data from a road traffic sensor located within a specific motorway of one of the mobility areas in the study. The results show that models trained with the fusion of both types of data, especially long short-term memory (LSTM) and Gated Recurrent Unit (GRU) neural networks, provide a more reliable prediction than models based only on the open data source. These results show that it is possible to predict the traffic entering a particular city in the next 30 minutes with an absolute error less than 10%. Thus, this work is a further step towards improving the prediction of human mobility in interurban areas by fusing open data with data from IoT systems

## How to cite this work

```elixir
@article{10.3897/jucs.94514,
	author = {Fernando  Terroso-Saenz and Andres Muñoz},
	title = {Human Mobility Prediction with Region-based Flows and Road Traffic Data},
	volume = {29},
	number = {4},
	year = {2023},
	doi = {10.3897/jucs.94514},
	publisher = {Journal of Universal Computer Science},
	issn = {0948-695X},
	pages = {374-396},
	URL = {https://doi.org/10.3897/jucs.94514},
	eprint = {https://doi.org/10.3897/jucs.94514},
	journal = {JUCS - Journal of Universal Computer Science}
}
```
