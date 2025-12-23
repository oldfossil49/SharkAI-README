# AI and paleontology: Effects of vertebrate fossil sample size on machine learning image classification

## Description

This archive contains original data, contextual information, and R source code in support of the above-referenced peer-reviewed article that was published in the journal *Paleobiology* (Cambridge University Press and the Paleontological Society). These items are archived here because they are considered ancillary to the manuscript, but are deemed necessary to further support, document, and elaborate upon the points made in the published article.

The *Paleobiology* article was published with the principal goal to use AI image classification of selected fossil shark taxa to understand a fundamental problem: How can machine learning algorithms process relatively small sample sizes, particularly in vertebrate paleontology?

**Paleobiology article doi:** [to be provided for README v. 2.0]

## Abstract of Published Paper

With the growing application of artificial intelligence (AI) and machine learning (ML), great potential exists to leverage these technologies in paleontology. Relative to many other scientific fields, a challenge of ML applied to paleontology is small sample sizes, particularly for fossil vertebrates. Shark teeth, abundant in the fossil record, provide a model system to use ML across varying sample sizes. Here we use six classes (taxa) of Neogene shark teeth for taxonomic identification, including a curated dataset of 3,150 images. Each class was evaluated using an 80% training and 20% validation split, with a separate, external test set of 25 samples per class. Pre-trained models perform well (accuracy > 90%), providing a strong baseline for classification. However, enabling fine-tuning of the ML model to identify fossil shark teeth improves performance considerably. Likewise, sample size per class also affects the accuracy of the models' classifications. Smaller sample sizes (n = 50 individuals per class) yielded a mean accuracy of 93.4%, but plateaued at 99% between 200 and 500 images per class. Confidence likewise increases with larger samples, from 81.8% (n = 50 individuals per class) to > 90% (n = 300 to 500 individuals per class). Misidentifications followed consistent patterns, reflecting morphological similarities and/or poor preservation. Artificially increasing the training datasets using data augmentation improves the confidence of identifications. This research indicates that relatively small samples of vertebrate species (50 to 500 individuals per class) can effectively train a ML model to identify these shark teeth with high levels of accuracy.

## Supplementary Materials—Table of Contents

(Abbreviation: ML, machine learning)
1. Contents and README
2. Complete study image data set
3. Optimal pixel density
   - a. Context
   - b. Statistical results
   - c. Database of ML model results
4. Original Python-Tensorflow files, including model code
5. Optimal performance, 50 to 500 samples per class
   - a. Statistical results
   - b. Database of ML model results without Fine Tuning
   - c. Database of ML model results with Fine Tuning
   - d. Database of variance
6. Data augmentation
   - a. Statistical results
   - b. Database of ML model results
7. Misidentification analysis
8. GBIF plots of fossil Lamnidae and Carcharhinidae
9. R code for data presented in sections 3, 5, and 6

## Authors/Affiliations

**Bruce J. MacFadden** (Corresponding author, see contacts below)  
Florida Museum of Natural History, University of Florida, Gainesville, Florida 32611, U.S.A.

**Cristobal A. Barberis**  
Adaptive Computing, 1100 5th Avenue S #201, Naples, Florida 34102, U.S.A.

**Maria C. Vallejo-Pareja**  
Florida Museum of Natural History, University of Florida, Gainesville, Florida 32611, U.S.A.

**Samantha P. Zbinden**  
Department of Integrative Biology, The University of Texas at Austin, Austin, Texas 78712, U.S.A.

**Victor J. Perez**  
Natural and Historic Resources Division, Prince George's County Parks and Recreation, Maryland-National Capital Park and Planning Commission, Upper Marlboro, Maryland 20772, U.S.A.

**Stephanie R. Killingsworth**  
Department of Geological Sciences, University of Florida, Gainesville, Florida 32611, U.S.A.

**Kenneth W. Marks** (unaffiliated participant)  
167356 S. Parker Road, Homer Glen, Illinois 60491, U.S.A.

**Devi Hall** (unaffiliated participant)  
541 Palm Drive, Key Largo, Florida 33037, U.S.A.

**Arthur Porto**  
Florida Museum of Natural History, University of Florida, Gainesville, Florida 32611, U.S.A.

## Acknowledgments

This project was supported by the Florida Museum of Natural History (Office of the Director) and U.S. National Science Foundation (project number 2157625). We thank L. Cone, B. Fite, and C. O'Connor, who allowed us to photograph important specimens in their private collections as part of our fossil study sets. S. Groff of the Calvert Marine Museum photographed some specimens, and University of Florida student A. Neilson assisted in the digital image processing and copyediting of this article. S. Moran of the North Carolina Museum of Natural Sciences curated and arranged for the loan of fossil shark specimens in his care that were used in this study. We thank Adaptive Computing (Naples, Florida) for the use of their computer infrastructure. This is University of Florida Contribution to Paleobiology 893. (Taken from the peer-reviewed article, with slight modifications.)

## Referenced Material

A complete list of these materials is provided in the Literature Cited section of the published article.

## Installation and Usage

Installation is generally not applicable in this data and information archive.

Usage
R code, provided in this contribution for specific instances of data generation and statistical analyses, can be enabled using R or R Studio open source software (R Core Team 2022).
The R code is presented in .R file format.
README file uses .md file format (e.g., can be accessed with github editor).
Sections containing text are presented in .rtf file format.
Data spreadsheet-style tables are presnetd in .csv file format.

## License

Follows guidelines of this archived source (Dryad).

## Known Issues/Bugs

Not applicable to this archive.

## Support/Help

Until further notice, contact the Corresponding author at:
- bmacfadd@ufl.edu
- brucemacfadden@gmail.com

## README Version History

**Version 1.0**, December 2025
