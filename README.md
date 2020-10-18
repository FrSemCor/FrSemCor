## FrSemCor, a corpus of semantically annotated French nouns

### The project

The project aims at compensating for the lack of semantically annotated data that can be used in both NLP and linguistics research. We provide a gold standard resource for French nouns, based on a careful semantic annotation designed. 

### Annotation guide

We have designed an [annotation guide](https://github.com/FrSemCor/FrSemCor/blob/master/guideAnno-FR-SemCor.pdf) (in French) during a preliminary annotation phase. Then 73% of the noun tokens from the 
[Sequoia corpus](https://deep-sequoia.inria.fr) corpus have been doubly-annotated by three French native students. They were adjudicated, and all noun tokens were validated by an expert. The remaining 27% of the tokens were annotated by an expert of the team.

### Resulting corpus
The resulting corpus contains 12,917 noun tokens, annotated into 24 supersenses (+ complex supersenses).
The FrSemCor annotations are released as 12th column of the Sequoia corpus, whose morpho-syntactic annotations are available in two syntactic annotation schemes (FTBdep and Universal Dependencies), cf. [Sequoia corpus](https://deep-sequoia.inria.fr) and (information on FrSemCor annotation format [here](https://github.com/FrSemCor/FrSemCor/blob/master/fr_semcor_format)).

Our annotation is compliant with the annotation of named entities and (nominal) multiword expressions performed in the [Parseme-fr](https://gitlab.lis-lab.fr/PARSEME-FR/PARSEME-FR-public/) project (available as 11th column).

The corpus is freely available, under the [LGPL-LR](https://spdx.org/licenses/LGPLLR.html) licence.

### Reference

If you use the corpus or need more information, please refer to:

Lucie Barque, Pauline Haas, Richard Huyghe, Delphine Tribout, Marie Candito, Benoît Crabbé and Vincent Segonne (2020) Annotating a French Corpus with Supersenses, Proceedings of LREC-2020, Marseille. 13-15 mai 2020. [preprint version](https://github.com/FrSemCor/FrSemCor/blob/master/Fr_SemCor_LREC2020.pdf)

