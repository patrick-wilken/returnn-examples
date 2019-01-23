Demos of how to combine datasets.

## CombinedDataset
CombinedDataset creates a new dataset containing all sequence of several others. The example here is a multi-lingual MT system that gets either German or French input and translates to English. For this purpose, the TranslationDatasets containing the de-en and fr-en corpora are combined into one. Run training with `rnn.py config.CombinedDataset`. After that, run search with `rnn.py config.CombinedDataset ++task search`.

## MetaDataset
MetaDataset creates a new dataset that provides corresponding sequences of several datasets at the same time. The example here is a multi-source MT system that gets both German and French input for a every sentence and translates to English. There are separate encoders for the two languages. Run training with `rnn.py config.MetaDataset`. After that, run search with `rnn.py config.MetaDataset ++task search`.
