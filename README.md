# Supervised-Morphological-Segmentation-System

Supervised morphological segmentation system using the `pycrfsuite` tagger.

## Description

Morphological segmentation is the task of splitting word forms into morphemes. In the notebook, I presented the baseline using [BPE](https://en.wikipedia.org/wiki/Byte_pair_encoding) and improved accuracy using [CRF](https://en.wikipedia.org/wiki/Conditional_random_field) (Feature engineering).

Evaluation Metric:
- F-score on segment boundaries (see notebook for more explanation)

Results:
- Baseline: 
    - Test set: F-score = 0.47

- CRF:
    - Dev set: F-score = 0.87
    - Test set: F-score = 0.85

Here is the [data source](http://mpsilfve.github.io/assets/segmentation_data.tgz).

## Credits

This task is designed and mentored by my instructor [Miikka Silfverberg](https://mpsilfve.github.io/) of my Morphology class COLX 525 in UBC.