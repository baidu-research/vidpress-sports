# Vidpress-Sports

*This is the official github repository for the Vidpress-Sports project in Baidu Research.*


## Baidu soccer embedding features for 550 complete soccer game videos in [SoccerNetv2](https://soccer-net.org/) 

We release our soccer embedding features [here](https://sports-multimodal-datasets.s3.amazonaws.com/Baidu_soccer_embeddings.zip). 89GB storage space is needed to download the zipped features.

The features can be used to reproduce our results in the CVPR 2021 ActivityNet Challange, Temporal Localization track, [SoccerNet Challenge](https://eval.ai/web/challenges/challenge-page/761/overview). We are ranked **No.1** in both action spotting task and replay grounding task.

The released embedding features are the concatenation of five features extracted using five finetuned video action recognition models. For details, please refer to our tech report on [arXiv](https://arxiv.org/pdf/2106.14447.pdf). The features can also be used to support other soccer video understanding research.

### Citation
If you find our features or tech report helpful, please cite:

```
@misc{zhoukangcheng2021,
      title={Feature Combination Meets Attention: Baidu Soccer Embeddings and Transformer based Temporal Detection}, 
      author={Xin Zhou and Le Kang and Zhiyu Cheng and Bo He and Jingyu Xin},
      year={2021},
      eprint={2106.14447},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
