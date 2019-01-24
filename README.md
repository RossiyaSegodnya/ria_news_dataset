# "Rossiya Segodnya" news dataset

This repository contains a news dataset presented in the paper:

Daniil Gavrilov, Pavel Kalaidin, and Valentin Malykh. Self-Attentive Model for Headline Generation. 41st European Conference on Information Retrieval, 2019. __[arXiv:1901.07786 [cs.CL]](https://arxiv.org/abs/1901.07786)__

## Description

Full dataset contains _1003869_ Russian language news documents from _January, 2010_ to _December, 2014_.

* [`ria_20.json`](./ria_20.json) contains the first 20 news documents from the dataset.

* [`ria_1k.json`](./ria_1k.json) contains the first 1000 news documents from the dataset.

* [`ria.json.gz`](./ria.json.gz) is full GZip'ed dataset.

A news document consists of two fields: `text` is a document body, while `title` is a news headline.

## License
This data is lisensed by Rossiya Segodnya news agency ([ria.ru](http://ria.ru)) under CC-BY-ND-NC license. The license text could be accessed [here](./LICENSE). The Russian version of the same license could be accessed [here](./LICENSE.ru).

## Misc
If you're using the data in a research please consider citing the mentioned paper:

    @inproceedings{gavrilov2018self,
    	title={Self-Attentive Model for Headline Generation},
    	author={Gavrilov, Daniil and  Kalaidin, Pavel and  Malykh, Valentin},
    	booktitle={Proceedings of the 41st European Conference on Information Retrieval},
    	year={2019}
    }
