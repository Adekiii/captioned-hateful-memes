# Caption-augmented Multimodal Classification of Hateful Memes

This is the repository for my thesis paper "Caption-augmented Multimodal Classification of Hateful Memes". The processes are divided into separate notebooks as described below:
- blip_augmentation.ipynb. This notebook shows the process of augmenting the Hateful Memes dataset with a BLIP2 model.
- feature_extraction.ipynb. In this notebook, CLIP, BERT are used as means to extract features from the data.
- roberta_extraction.ipynb. Since the idea of experimenting with RoBERTa as well came a bit later into the process, this was done in a separate notebook.
- bert_model.ipynb and roberta_model.ipynb. The original models without captions are trained and evaluated in these notebooks.
- bert_model_blip2.ipynb and roberta_model_blip2.ipynb. The captioned models are trained and evaluated in these notebooks.
- manual_assessment.ipynb. This notebook contains details about the manual assessment of caption quality as described in the Discussion section of the paper.

This project uses the Facebook Hateful Memes dataset. These can not be provided due to licensing by Facebook, they are able to be downloaded from https://hatefulmemeschallenge.com/.
