# Vidpress-Sports

*This is the official github repository for the Vidpress-Sports project in Baidu Research.*


## Baidu soccer embedding features for 550 complete soccer game videos in [SoccerNetv2](https://soccer-net.org/) 

We release our soccer embedding features on AWS S3.

How to download:
1) Follow instructions [here](https://github.com/aws/aws-cli/tree/v2) to install aws-cli
2) Run the following command: `aws s3 cp --recursive s3://sports-multimodal-datasets/Baidu_soccer_embeddings/ <local_folder>`

*The google drive link for downloading the features will be provided soon.*

The features can be used to reproduce our results in the CVPR 2021 ActivityNet Challange, Temporal Localization track, [SoccerNet Challenge](https://eval.ai/web/challenges/challenge-page/761/overview). We are ranked **No.1** in both action spotting task and replay grounding task.

The released embedding features are the concatenation of five features extracted using five finetuned video action recognition models. For details, please refer to our tech report on arXiv (will be posted soon). The features can also be used to support other soccer video understanding research.



