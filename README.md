# [Topic-Based Unsupervised and Supervised Dictionary Induction](https://doi.org/10.1145/3564698)
> Yuzhi Liu, Massimo Piccardi  
> Published in *ACM Transactions on Asian and Low-Resource Language Information Processing*, Volume 22, Issue 3 &bull; Article No.: 77  
> March 2023

## Abstract
Word translation is a natural language processing task that provides translation between the words of a source and a target language. As a task, it reduces to the induction of a bilingual dictionary, which is typically performed by aligning word embeddings of the source language to word embeddings of the target language. To date, all the existing approaches have focused on performing a single, global alignment in word embedding space. However, semantic differences between the various languages, in addition to differences in the content of the corpora used for training the word embeddings, can hinder the effectiveness of such a global alignment. For this reason, in this article we propose conducting the alignment between the source and target embedding spaces by multiple mappings at topic level. The experimental results show that our approach has been able to achieve an average accuracy improvement of +3.30 percentage points over a state-of-the-art approach in unsupervised dictionary induction from languages as diverse as German, French, Italian, Spanish, Finnish, Turkish, and Chinese to English, and +3.95 points average improvement in supervised dictionary induction.

## Key Results
- Average accuracy improvement of +3.30 percentage points over a state-of-the-art approach in unsupervised dictionary induction.
- +3.95 points average improvement in supervised dictionary induction.

## Keywords
Topic-based dictionary induction, Word embedding alignment, Dictionary induction, Word translation, Topic modeling

## Citation
```bibtex
@article{10.1145/3564698,
author = {Liu, Yuzhi and Piccardi, Massimo},
title = {Topic-Based Unsupervised and Supervised Dictionary Induction},
year = {2023},
issue_date = {March 2023},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {22},
number = {3},
issn = {2375-4699},
url = {https://doi.org/10.1145/3564698},
doi = {10.1145/3564698},
journal = {ACM Trans. Asian Low-Resour. Lang. Inf. Process.},
month = {mar},
articleno = {77},
numpages = {21}
}
