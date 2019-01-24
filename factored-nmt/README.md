Implementation of [Factored Neural Machine Translation](https://arxiv.org/abs/1609.04621).
Tested on dummy translation task from English to both German and French. German and French words are used as the two factors.

Run training with `rnn.py config`. After that, run search with `rnn.py config ++task search`. For now, use this branch: https://github.com/patrick-wilken/returnn/tree/FactoredNMT2.
