# "Rossiya Sevodnya" news dataset

This repository contains a news dataset presented in the paper:

Daniil Gavrilov, Pavel Kalaidin, and Valentin Malykh. Self-Attentive Model for Headline Generation. 41st European Conference on Information Retrieval, 2019.

`LINK TO THE PAPER`

## Description

* [`ria_1k.json`](./ria_1k.json) contains the first 1000 news documents from the dataset.

* [`ria.json.gz`](./ria.json.gz) is full GZip'ed dataset.

A news document consists of two fields: `text` is a document body, while `title` is a news headline.

## License
This data is lisensed by Rossiya Sevodnya news agency ([ria.ru](http://ria.ru)) and JSC VKontakte ([VK.com](https://vk.com)) under CC-BY-ND-NC license. The license text could be accessed [here](./LICENSE). The Russian version of the same license could be accessed [here](./LICENSE.ru).

## Misc
If you're using the data in a research please consider citing the mentioned paper:

    @inproceedings{gavrilov2018self,
    	title={Self-Attentive Model for Headline Generation},
    	author={Gavrilov, Daniil and  Kalaidin, Pavel and  Malykh, Valentin},
    	booktitle={Proceedings of the 41st European Conference on Information Retrieval},
    	year={2019}
    }
