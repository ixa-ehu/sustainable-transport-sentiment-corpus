## A Corpus for Sentiment Analysis of Sustainable Transport

This repo includes a new dataset, the Gold Standard Corpus (GSC) on Sentiment Analysis for Transport, derived from user reviews about transport, which has been manually annotated. The dataset covers a range of transportation modes according to their sustainability.

More specifically, the new dataset contains 2000 reviews from the transport domain, manually annotated as positive or negative. This corpus is the first of its kind for the transport domain that is publicly available. The annotation process showed that the original classification of TripAdvisor comments according to a scale of 1–5 stars does not necessarily correspond with the real polarity. When manually reviewing these comments, we found that around 25% of the rates had to be manually corrected.

### Datasets

+ User Gold Standard Corpus: [GSC Gold Standard Corpus](https://github.com/ixa-ehu/sustainable-transport-sentiment-corpus/tree/main/ugc_gold_standard)
+ Binary Classification Experiments (with noise): [Datasets and Notebook](https://github.com/ixa-ehu/sustainable-transport-sentiment-corpus/tree/main/binary_classification
+ Multiclass Classification Experiments (1-5 stars): [Datasets and Notebook](https://github.com/ixa-ehu/sustainable-transport-sentiment-corpus/tree/main/multiclass_classification)

**NOTE** The notebooks use the scripts contained in this repo: [https://github.com/ragerri/transformers-training-scripts](https://github.com/ragerri/transformers-training-scripts)

### More Details and Citation

+ Ainhoa Serna, Aitor Soroa, Rodrigo Agerri. Applying Deep Learning Techniques for Sentiment Analysis to Assess Sustainable Transport. Sustainability. 2021; 13(4):2397. [https://doi.org/10.3390/su13042397](https://doi.org/10.3390/su13042397)

+ [Click here to download bibtex reference](https://github.com/ixa-ehu/sustainable-transport-sentiment-corpus/blob/main/reference.bib)
