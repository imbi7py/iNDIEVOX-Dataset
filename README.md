![iNDIEVOX](https://raw.githubusercontent.com/indievox-inc/iNDIEVOX-Dataset/master/image/logo.png)

## Intro

iNDIEVOX open datasets, you can play machine learning algorithms with these datasets.

## Datasets

### Music Valence-Arousal Datasets

You can check out and listen to the music by song id, using the url format like: https://www.indievox.com/song/song_id. for example: [https://www.indievox.com/song/1](https://www.indievox.com/song/1)

* [Valence-Arousal Dataset Song ID List](https://github.com/indievox-inc/iNDIEVOX-Dataset/blob/master/dataset/va_song_id.dataset) - Top 200 song ids are for testing and the other 800 song ids are for training.
* [Valence Training Dataset](https://github.com/indievox-inc/iNDIEVOX-Dataset/blob/master/dataset/valence_train.dataset) - Top 68 columns are audio features and the last column is valence value.
* [Valence Testing Dataset](https://github.com/indievox-inc/iNDIEVOX-Dataset/blob/master/dataset/valence_test.dataset) - Top 68 columns are audio features and the last column is valence value.
* [Arousal Training Dataset](https://github.com/indievox-inc/iNDIEVOX-Dataset/blob/master/dataset/arousal_train.dataset) - Top 68 columns are audio features and the last column is arousal value.
* [Arousal Testing Dataset](https://github.com/indievox-inc/iNDIEVOX-Dataset/blob/master/dataset/arousal_test.dataset) - Top 68 columns are audio features and the last column is arousal value.


## Algorithms and Feature Extraction

We play algorithms like [Gaussian SVM](https://en.wikipedia.org/wiki/Support_vector_machine) and [Ridge Regression](https://en.wikipedia.org/wiki/Tikhonov_regularization) to train data from the datasets. The algorithm library we use is [Fuku-ML](https://github.com/fukuball/fuku-ml), and feature extraction library is [PyAudio](https://github.com/jleb/pyaudio).

## Made From These Datasets
