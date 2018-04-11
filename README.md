
This repository will host the dataset described in the following paper:

> OneStopEnglish corpus: A new corpus for automatic readability assessment and text simplification  
> authors: Sowmya Vajjala and Ivana Lučić  
> (to appear) In the proceedings of The 13th Workshop on Innovative Use of NLP for Building Educational Applications, 2018  
> (more details to come soon)

Please cite the above paper if you use this corpus in your research.

**Description of this repo:**
- Texts-SeparatedByReadingLevel/: This is the actual corpus folder, containing three sub-folders, one per reading level. Each file has the same name followed by a -ele.txt/-int.txt/-adv.txt depending on the sub-folder it is in.  
- Texts-Together-OneCSVperFile/: This folder has one csv file per text, three columns for three reading levels. Paragraph breaks are preserved.  
- Sentence-Aligned/: This folder contains three text files, with pair-wise sentence alignments (adv-int, int-ele, adv-ele). Cosine similarity was used to align sentences. 
- Processed-AllLevels-AllFiles/ : folder contains sub-folders with output files from Stanford parser, Stanford CoreNLP, and [Upenn's Discourse Connectives Tagger](http://www.cis.upenn.edu/~nlp/software/discourse.html)

**For enquiries:**
contact: sowmya@iastate.edu
