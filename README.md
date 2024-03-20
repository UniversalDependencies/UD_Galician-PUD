# Summary

The Galician PUD is a treebank for Galician developed at CiTIUS (Universidade de Santiago de Compostela).

# Introduction

There are 1000 sentences in each language, always in the same order. (The sentence alignment is 1-1 but occasionally a sentence-level segment actually consists of two real sentences.) The sentences are taken from the news domain (sentence id starts in ‘n’) and from Wikipedia (sentence id starts with ‘w’). There are usually only a few sentences from each document, selected randomly, not necessarily adjacent. The digits on the second and third position in the sentence ids encode the original language of the sentence. The first 750 sentences are originally English (01). The remaining 250 sentences are originally German (02), French (03), Italian (04) or Spanish (05) and they were translated to other languages via English. Translation into German, French, Italian, Spanish, Arabic, Hindi, Chinese, Indonesian, Japanese, Korean, Portuguese, Russian, Thai and Turkish has been provided by DFKI and performed (except for German) by professional translators. Then the data has been annotated morphologically and syntactically by Google according to Google universal annotation guidelines; finally, it has been converted by members of the UD community to UD v2 guidelines.

Additional languages have been provided (both translation and native UD v2 annotation) by other teams: Czech by Charles University, Finnish by University of Turku and Swedish by Uppsala University.

The entire treebank is labeled as test set (and was used for testing in the shared task). If it is used for training in future research, the users should employ ten-fold cross-validation.

The linguistic annotation was first carried out using state-of-the-art NLP tools for Galician, and then reviewed by two experts, achieving a high inter-annotator agreement.

# Changelog

* 2024-05-15 v2.14
  * Initial release in Universal Dependencies.

# Acknowledgments

* Marcos Garcia. 2016. *Universal Dependencies Guidelines for the Galician-Treegal Treebank.* Technical Report. LyS Group, Universidade da Coruña.

* Xulia Sánchez-Rodríguez, Albina Sarymsakova, Laura Castro, and Marcos Garcia. 2024. Increasing manually annotated resources for Galician: the Parallel Universal Dependencies Treebank. In *Proceedings of the 16th International Conference on Computational Processing of Portuguese*, pages 587–592, Santiago de Compostela, Galicia/Spain. Association for Computational Lingustics.

We would also like to thank Pablo Gamallo and Iria de-Dios-Flores for helpful discussions and feedback, and Laura Castro, Sandra Rodríguez Rey and Helena Pérez Puente for their assistance with the translations.

## References

If you use the Galician PUD treebank, you are encouraged to cite this paper:
<pre>
@inproceedings{sanchez-rodriguez-etal-2024-increasing,
    title = "Increasing manually annotated resources for {G}alician: the Parallel {U}niversal {D}ependencies Treebank",
    author = "S{\'a}nchez-Rodr{\'\i}guez, Xulia  and
      Sarymsakova, Albina  and
      Castro, Laura  and
      Garcia, Marcos",
    editor = "Gamallo, Pablo  and
      Claro, Daniela  and
      Teixeira, Ant{\'o}nio  and
      Real, Livy  and
      Garcia, Marcos  and
      Oliveira, Hugo Gon{\c{c}}alo  and
      Amaro, Raquel",
    booktitle = "Proceedings of the 16th International Conference on Computational Processing of Portuguese",
    month = mar,
    year = "2024",
    address = "Santiago de Compostela, Galicia/Spain",
    publisher = "Association for Computational Lingustics",
    url = "https://aclanthology.org/2024.propor-1.65",
    pages = "587--592",
}
</pre>


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Genre: news wiki
Includes text: yes
Lemmas: manual native
UPOS: manual native
XPOS: manual native
Features: automatic with corrections
Relations: manual native
Contributors: Sarymsakova, Albina; Sánchez-Rodríguez, Xulia; Garcia, Marcos
Contributing: elsewhere
Contact: marcos.garcia.gonzalez@usc.gal
===============================================================================
</pre>
