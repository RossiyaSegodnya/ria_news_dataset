###### Russian news agency “Rossiya Sevodnya" news dataset

This repository contains news dataset presented in the paper:

Daniil Gavrilov, Pavel Kalaidin, and Valentin Malykh, Self-Attentive Model for Headline Generation, 41st European Conference on Information Retrieval.

`LINK TO THE PAPER`

Description:

`ria_1k.json` contains the first 1k news.

`ria.json.gz` contains full dataset. [link](https://github.com/kalaidin/news_dataset/raw/master/ria.json.gz) to start downloading.

`text` is the news body, while `title` is the news headline.

This data is lisensed by Rossiya Sevodnya news agency ([ria.ru](http://ria.ru)) and JSC VKontakte ([VK.com](https://vk.com)) under CC-BY-ND-NC license. The license could be accessed [here](./LICENSE). The Russian version of the same license could be accessed [here](./LICENSE.ru).

If you're using the data please consider citing the mentioned paper:

    @inproceedings{gavrilov2018self,
    	title={Self-Attentive Model for Headline Generation},
    	author={Gavrilov, Daniil and  Kalaidin, Pavel and  Malykh, Valentin},
    	booktitle={Proceedings of the 41st European Conference on Information Retrieval},
    	year={2019}
    }
