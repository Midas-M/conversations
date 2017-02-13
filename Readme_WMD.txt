The WMD module accepts two folders where the corresponding summaries must have identical names.
It also accepts a dictionary with the word-word_embedding that must be pre-extracted from the corpora.
It returns the distance.
The module runs on top of Earth Mover's Distance which has been compiled for unix java-1.8.
The original package of earth mover distance plus instructions, that must be recompiled for any other distribution can be found here:
https://github.com/dkoslicki/EMDeBruijn

Additionally in order to reproduce the results one can use the gensim package which offers a wmd implementation and compare the corresponding summaries. 