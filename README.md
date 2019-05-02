# Summary

Universal Dependencies treebank is based on data samples extracted from Taiga Corpus and MorphoRuEval-2017 text collections.

# Introduction

UD Russian Taiga has been developed at the School of Linguistics, National Research University Higher School of Economics in Moscow (HSE/Vyshka). The selection of texts is meant to represent those registers that have not been covered by UD Russian SynTagRus and UD Russian Google Stanford Dependencies, mainly e-communication (blogs and social media). The sentences are extracted from two open data collections. Taiga Corpus ([https://tatianashavrina.github.io/taiga_site/](https://tatianashavrina.github.io/taiga_site/)) is an open-source corpus for machine learning collected by students as part of the curriculum of the MA Program in Computational Linguistics at HSE. MorphoRuEval 2017 text collections ([https://github.com/dialogue-evaluation/morphoRuEval-2017](https://github.com/dialogue-evaluation/morphoRuEval-2017)) is an output of the RuEval shared task 'Evaluation of Russian NLP: Morphological analysis, [http://www.dialog-21.ru/en/evaluation/2017/morphology/](http://www.dialog-21.ru/en/evaluation/2017/morphology/)).

The plain text data were tokenized, lemmatized and parsed using UDpipe ([http://ufal.mff.cuni.cz/udpipe](http://ufal.mff.cuni.cz/udpipe)) and checked manually. Corrections were made at all levels: tokenization, lemmata, pos, features, dependency relations.

# Registers

* blogs and social media: 65%
main source: vk.com, instagram, facebook, twitter

* poetry: 34% 
main source: stihi.ru (naïve poetry), Corpus of Russian poetry (RNC)

* news: 1%
The tiny news collection was used to train annotators and check annotation consistency with other UD treeabnks.


# Data split

* v.2.4:
  * train: 43.0% (16.6K tokens, 1302 sentences)  
  * dev: 26.1% (10.1K tokens, 945 sentences)
  * test: 30.8% (11.9K tokens, 1017 sentences)

* v.2.2:
  * train: 50% (10K tokens, 880 sentences)  
  * test:  50% (10K tokens, 884 sentences)  

# Acknowledgments

We are grateful to all the contributors to the original open Russian data collections and especially to Tatiana Shavrina (Taiga) and Alena Fenogenova (MorphoRuEval-2017 data set).

## References

* Lyashevskaya, Olga, Kira Droganova, Daniel Zeman, Maria Alexeeva, Tatiana Gavrilova, Nina Mustafina, and Elena Shakurova.
(2016). Universal Dependencies for Russian: a New Syntactic Dependencies Tagset. In: Series: Linguistics, WP BRP 44/LNG/2016. Moscow.

* Sorokin, Andrey, Tatiana Shavrina, Olga Lyashevskaya, Victor Bocharov, Svetlana Alexeeva, Kira Droganova, Alena Fenogenova, and Dmitry Granovsky. (2017). MorphoRuEval-2017: an Evaluation Track for the Automatic Morphological Analysis Methods for Russian. In Computational Linguistics and Intellectual Technologies, Proceedings of Dialog 2017, Moscow. No 16 (23). Vol. 1, 297-313.

* Lyashevskaya, Olga, Victor Bocharov, Alexey Sorokin, Tatiana Shavrina, Dmitry Granovsky, and Svetlana Alexeeva. (2017).
Text collections for evaluation of Russian morphological taggers. Jazykovedny Casopis, 68 (2), 2017: 258-267.

* Shavrina, Tatiana, Olga Shapovalova. (2017) To the methodology of corpus construction for machine learning: «Taiga» syntax tree corpus and parser. In Proceedings of the International Conference "CORPORA 2017", Saint-Petersbourg, Russia.


# Changelog

* 2019-05-01 v2.4
  * Major changes
  * UPOS, FEAT, DEPREL manually fixed
  * New texts (genre: poetry social) added.

* 2019-01-21 v2.3+
  * Dev added, train expanded, UPOS, FEAT, HEAD, DEPREL updated in accordance with the UD2 guidelines, minor tokenization updates

* 2018-07-01 v2.2
  * First official release.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.2
License: CC BY-SA 4.0
Includes text: yes
Genre: blog news poetry social
Lemmas: manual native
UPOS: manual native
XPOS: manual native
Features: manual native
Relations: manual native
Contributors: Lyashevskaya, Olga; Rudina, Olga
Contributing: elsewhere
Contact: olesar@yandex.ru
===============================================================================
</pre>
