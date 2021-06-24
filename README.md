## ruGPT3 solution of RuSimpleSentEval (RSSE)

### Approach

Solution of [RuSimpleSentEval](https://github.com/dialogue-evaluation/RuSimpleSentEval), competition in Dialogue2021.
Overall **37 SARI** score.

Solution based on RuGPT-3XL. Model was tuned on the train data.

Our approach has achieved second place on the public leaderboard and fifth place on the privateleaderboard. 


## Usage

* Download pre-trained XL model [here](https://disk.yandex.ru/d/dd7tM93w4g-14g) and put in folder `model`.

* Example of usage is [here](./Simplification%20with%20ruGPT3.ipynb)

* Explore all experiments in the [article](http://www.dialog-21.ru/media/5250/fenogenovaa141.pdf).

Text Simplification is the task of reducing the complexity of the vocabulary and sentence structure of the text
while retaining its original meaning with the goal of improving readability and understanding. We explore the
capability of the autoregressive models such as RuGPT3 (Generative Pre-trained Transformer 3 for Russian) to
generate high quality simplified sentences. Within the shared task RuSimpleSentEval we present our solution
based on different usages of RuGPT3 models. The following setups are described: 1) few-shot unsupervised
generation with the RuGPTs models 2) the effect of the size of the training dataset on the downstream performance
of fine-tuned model 3) 3 inference strategies 4) the downstream transfer and post-processing procedure using pretrained paraphrasers for Russian. This paper presents the second-place solution on the public leaderboard and the
fifth-place solution on the private leaderboard. The proposed method is comparable with the novel state-of-the-art
approaches. Additionally, we analyze the performance and discuss the flaws of RuGPTs generation.

## Cite us
```@article{fenogenovatext,
  title={Text Simplification with Autoregressive Models},
  author={Fenogenova, Alena and Sberbank, SberDevices}}
  ```

[Paper pdf](http://www.dialog-21.ru/media/5250/fenogenovaa141.pdf)
![](https://habrastorage.org/webt/rf/ow/ym/rfowymv4tezksyy7lu6siaseero.png)

## DataFest presentation
To see the video, click on the screenshot => <a style="float:right" href="https://youtu.be/V-fp4V6FHlo" target="_blank">
  <img alt="DataFest Video" src="https://habrastorage.org/webt/vl/dv/m5/vldvm5lvzogpaih881-tuvcl8py.png" />
</a>
