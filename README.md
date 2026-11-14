# afc_classification
A repository for the dataset and code of an AFC system.

## Files

The files contained in this repository are:
>dataset.jsonl: The 3-label unified dataset, as described in the article.
>
>corpus.ipynb: The code used to generate the dataset. It is advised not to re-run unless necessary.
>
>model.ipynb: The complete notebook that trains the supervised classifiers and retrieval-augmented generation.
>
>data/*: The files from the datasets required for the dataset. Due to its size, data/wiki-pages from the FEVER dataset was not included.
>
>This will cause errors in corpus.ipynb unless the files is locally sourced.
