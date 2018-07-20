
This repository hosts the dataset described in the following paper:

> OneStopEnglish corpus: A new corpus for automatic readability assessment and text simplification  
> Sowmya Vajjala and Ivana Lučić  
> 2018  
> Proceedings of the Thirteenth Workshop on Innovative Use of NLP for Building Educational Applications, pages 297–304. Association for Computational Linguistics.  
> [url](http://aclweb.org/anthology/W18-0535). [bib file](https://aclanthology.coli.uni-saarland.de/papers/W18-0535/w18-0535.bib)

Please cite the above paper if you use this corpus in your research.

[![DOI](https://zenodo.org/badge/128919409.svg)](https://zenodo.org/badge/latestdoi/128919409)

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

**Description of this repo:**
- Texts-SeparatedByReadingLevel/: This is the actual corpus folder, containing three sub-folders, one per reading level. Each file has the same name followed by a -ele.txt/-int.txt/-adv.txt depending on the sub-folder it is in.  
- Texts-Together-OneCSVperFile/: This folder has one csv file per text, three columns for three reading levels. Paragraph breaks are preserved.  
- Sentence-Aligned/: This folder contains three text files, with pair-wise sentence alignments (adv-int, int-ele, adv-ele). Cosine similarity was used to align sentences. 
- Processed-AllLevels-AllFiles/ : folder contains sub-folders with output files from Stanford parser, Stanford CoreNLP, and [Upenn's Discourse Connectives Tagger](http://www.cis.upenn.edu/~nlp/software/discourse.html)

**For enquiries:**
contact: sowmya@iastate.edu
