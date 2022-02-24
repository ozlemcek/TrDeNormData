# Turkish-German Code-switching Normalisation Data

This repository contains Turkish-German code-switched tweets prepared to be used in lexical normalisation. 


The whole dataset has 1029 tweets. Train:test split is 800:229. There is no separate development set.
There are 12 fine-grained language IDs (see (Çetinoğlu, 2016) below) and 17 POS tags of Universal Dependencies.

The version used in (van der Goot and Çetinoğlu, 2021) has coarse-grained language IDs and the training set is
split into 10 folds for cross-validation. This version can be accessed from https://bitbucket.org/robvanderg/csmonoise/.

Only the training set is publicly available at the moment, as the data will be part of the W-NUT 2021 Shared Task [MultiLexNorm: Multilingual Lexical Normalization](http://noisy-text.github.io/2021/multi-lexnorm.html).
Please contact Özlem Çetinoğlu (ozlem.cetinoglu@ims.uni-stuttgart.de) for the test set.


## Publications

#### Adding normalisation-only layers, token-level alignment, adapting language IDs and POS tags to normalisation-only layers

Rob van der Goot and Özlem Çetinoğlu\
*Lexical Normalization for Code-switched Data and its Effect on POS Tagging*\
In the Proceedings of the 16th Conference of the European Chapter of the Association for Computational Linguistics (EACL), April 2021, Kyiv, Ukraine.

https://aclanthology.org/2021.eacl-main.200.pdf

```
@inproceedings{csnorm2021,
    title = "Lexical Normalization for Code-switched Data and its Effect on POS Tagging",
    author = "van der Goot, Rob and \c{C}etino{\u{g}}lu, \"O}zlem",
    booktitle = "Proceedings of the 16th Conference of the {E}uropean Chapter of the Association for Computational Linguistics: Volume 1, Long Papers",
    year = "2021",
    publisher = "Association for Computational Linguistics",
}
```


#### Segmentation and POS tag annotation

Özlem Çetinoğlu and Çağrı Çöltekin\
*Part of Speech Annotation of a Turkish-German Code-Switching Corpus*\
In the Proceedings of the 10th Linguistic Annotation Workshop (LAW-X), August 2016, Berlin, Germany.

http://www.aclweb.org/anthology/W/W16/W16-1714.pdf

```
@inproceedings{cetinoglu-coltekin-2016-part,
    title = "Part of Speech Annotation of a {T}urkish-{G}erman Code-Switching Corpus",
    author = {{\c{C}}etino{\u{g}}lu, {\"O}zlem  and {\c{C}}{\"o}ltekin, {\c{C}}a{\u{g}}r{\i}},
    booktitle = "Proceedings of the 10th Linguistic Annotation Workshop held in conjunction with {ACL} 2016 ({LAW}-X 2016)",
    month = aug,
    year = "2016",
    address = "Berlin, Germany",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W16-1714",
    doi = "10.18653/v1/W16-1714",
    pages = "120--130",
}
```

#### Data collection, normalisation, tokenisation, annotation with code-switching boundaries and language IDs

Özlem Çetinoğlu\
*A Turkish-German Code-Switching Corpus*\
In the Proceedings of the 10th edition of the Language Resources and Evaluation Conference (LREC), May 2016, Portorož, Slovenia.

http://www.lrec-conf.org/proceedings/lrec2016/pdf/1151_Paper.pdf

```
@InProceedings{cetinoglu16.1151,
  author = {Özlem Çetinoğlu},
  title = {A Turkish-German Code-Switching Corpus},
  booktitle = {Proceedings of the Tenth International Conference on Language Resources and Evaluation (LREC 2016)},
  year = {2016},
  month = {may},
  date = {23-28},
  location = {Portorož, Slovenia},
  editor = {Nicoletta Calzolari (Conference Chair) and Khalid Choukri and Thierry Declerck and Sara Goggi and Marko Grobelnik and Bente Maegaard and Joseph Mariani and Helene Mazo and Asuncion Moreno and Jan Odijk and Stelios Piperidis},
  publisher = {European Language Resources Association (ELRA)},
  address = {Paris, France},
  isbn = {978-2-9517408-9-1},
  language = {english}
 }

```
