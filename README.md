# Cross-datasets-generalization-for-Covid-related-hate-speech-detection

#### in this project we aimed to see whether can we use the data sets that have already been labelled or annotated to train a model, then test on a small amount number of covid related hate speech. in this experiment we did several cross data sets generalization tests using different data sets and models.
### This notebook gives an introduction to working with the various data sets in Wikipedia Talk and data from other platforms. The release includes:
1. five different datasets used in this experiment: AC(attack comment), Toxicity, Gab and EA(easet asians prejudice) as training datasets. one dataset called 
  covid racism, which contains 2319 examples with labels as test set.
2. two classifiers were used: BERT and RoBERTa plus additional linear linears.

Please refer to our documentation of the schema of each data set and research papers for documentation on the data collection and modeling methodology.

### for datasets downloads:
#### AC: https://figshare.com/articles/dataset/Wikipedia_Talk_Labels_Personal_Attacks/4054689
#### Toxicity: https://meta.wikimedia.org/wiki/Research:Detox/Data_Release
#### Gab hate corpus: https://osf.io/edua3/
#### EA data: https://arxiv.org/abs/2005.03909
