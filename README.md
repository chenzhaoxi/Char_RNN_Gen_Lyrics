# Lyrics generator

A keras implementation of Karpathys char-rnn (https://github.com/karpathy/char-rnn) and the blog(http://karpathy.github.io/2015/05/21/rnn-effectiveness/). it is trained in a many-to-many fashion.

We are tring to build a network to write lyrics with a style. Training data is in cp.txt.(Coldplay's all lyrics).

## To load data and train the model:
gen_lyrics.ipynb

## To generate lyrics:
You can directly use the model store in lyrics_pre.h5 by running generate.ipynb
