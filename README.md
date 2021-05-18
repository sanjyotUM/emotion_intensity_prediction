# Tweet emotion intensity prediction 

Detect intensity for 4 different emotions from the tweet content.

Key techniques used for feature engineering:

- Emoji extraction and interpretation
- Hashtag extraction and segmentation
- Spelling correction
- Accent/Diacritic removal
- Emotion synonym similarity/antonym dissimilarity using word embeddings
- Cuss word detection
- Extracting other token properties


## Notebook description

`notebooks/pipeline.ipynb`: Constructing the tokenizer and feature engineering.

`notebooks/training.ipynb`: Training and evaluation of all classifiers.
