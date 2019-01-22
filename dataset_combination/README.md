Demos of how to combine datasets.

To create a new dataset containing all sequence of several others, use CombinedDataset. The example is a multi-lingual MT system from German and French to English where all parameters are shared. Note, that the de-en and fr-en corpora are combined into one using CombinedDataset. Run training with `rnn.py config.CombinedDataset`. After that, run search with `rnn.py config.CombinedDataset ++task search`.
