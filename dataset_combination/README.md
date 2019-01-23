Demos of how to combine datasets.

## CombinedDataset
CombinedDataset creates a new dataset containing all sequence of several others. The example here is a multi-lingual MT system from German and French to English where all parameters are shared. For this purpose, the TranslationDatasets containing the de-en and fr-en corpora are combined into one. Run training with `rnn.py config.CombinedDataset`. After that, run search with `rnn.py config.CombinedDataset ++task search`.
