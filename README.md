# Bitcoin-Datathon

## Context
This dataset is composed of various files corresponding to 2 days of activity in the Bitcoin Blockchain.
The files are not stored in this GitHub repository due to size constraints, but are available in this folder: http://cazabetremy.fr/datasets/bitcoin2days

A first series of files [addresses](http://cazabetremy.fr/datasets/bitcoin2days/addresses.csv),[transactions](http://cazabetremy.fr/datasets/bitcoin2days/transactions.csv),[blocks](http://cazabetremy.fr/datasets/bitcoin2days/blocks.csv),[outputs](http://cazabetremy.fr/datasets/bitcoin2days/outputs.csv),[inputs](http://cazabetremy.fr/datasets/bitcoin2days/inputs.csv) correspond approximately to the raw data from the blockchain, enriched with additionnal information such as entities names when known.

Another file corresponds to a simplified view, a **network** view, in which each line corresponds to a transaction from one entity to another entity. In this form, some information is lost, but it can be simpler to manipulate. The data is provided in two formats, [network.csv](http://cazabetremy.fr/datasets/bitcoin2days/2days_entity_network.csv) and [network.parquet](http://cazabetremy.fr/datasets/bitcoin2days/2days_entity_network.parquet).

## Getting started
The best way to getting started with those files is by following their corresponding notebooks, that explain the content and show how to start analyzing them.
These notebooks are in this repository:
* [Bitcoin Transaction Data](https://github.com/Yquetzal/Bitcoin-Datathon/blob/main/Bitcoin%20Transaction%20Data.ipynb)
* [Entity Network 101](https://github.com/Yquetzal/Bitcoin-Datathon/blob/main/Entity_network_101.ipynb)

Note: this notebooks are ready to run in google colab or any other online notebook editor.



## Origin
This data has first been proposed as part of a Datathon/Hackathon (http://alter-crypto.sci-web.net/#HACKATHON), and is also used for various classes, such as (http://cazabetremy.fr/Teaching/bitcoinClass/BitcoinNetwork.html).


