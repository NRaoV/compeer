# compeer
__compeer__ is a library that uses machine learning algorithms to perform fuzzy matching that helps identify two elements of text, strings, or entries that are approximately similar but are not exactly the same.

__compeer__ will help you:

* __Merging Records:__ Gathering all the data comes from different sources about an entity and merging/joining them into a single record. This technique often requires fuzzy string matching to value in the identity column of the records.
* __Data accuracy:__ Improve data quality and accuracy by data deduplication, identification of false-positives etc. which becomes extremely crucial to ensure that good quality data is fed to these machine learning models
* __Detecting fraudulent data:__ Deduplication and pattern matching techniques are heavily used to single out records with fradulent behavior out of large data set.
* __Spelling corrector:__ Finding the most probable corrections simply by combining fuzzy string matching with probability theory to construct a simple but efficient spelling corrector

compeer takes in training data and comes up with the best rules for your dataset to quickly and automatically find similar records, even with very large databases.

## Objectives
* Match and report similarity metrics of structured data efficiently (Comparing M * N, 1 * N cases)
* Provides multiple ways of matching for ex: character by character, sequencing of words, sounding similar, etc.,
* Work on complex structures such as Date, Address, person names
* Suggests semantically nearest words for the mispelt or words in short form

## Installation

## Testing

## Errors / Bugs

## Note on Patches/Pull Requests
 
* Fork the project.
* Make your feature addition or bug fix.
* Send us a pull request. Bonus points for topic branches.

## Copyright

Copyright (c) 2022 NRaoV. Released under the [MIT License](https://github.com/NRaoV/compeer/blob/main/LICENSE).

Third-party copyright in this distribution is noted where applicable.

## Citing compeer
If you use compeer in an academic work, please give this citation:

NRaoV. 2022. Compeer. https://github.com/NRaoV/compeer.

## Reference
1. [*Learnable Similarity Functions and their Application to Record Linkage and Clustering*](http://www.cs.utexas.edu/~ml/papers/marlin-dissertation-06.pdf).
2. [*How to Write a Spelling Corrector*](http://norvig.com/spell-correct.html).
3. [*Fuzzy Logic Tutorial: What is, Architecture, Application, Example*](https://www.guru99.com/what-is-fuzzy-logic.html).
4. [*Measuring the Business Value of Data Quality*](https://www.data.com/export/sites/data/common/assets/pdf/DS_Gartner.pdf)
5. [*How Best In Class Fuzzy Matching Solutions Work*](https://dataladder.com/whitepapers/how-best-in-class-fuzzy-matching-solutions-work-combining-established-and-proprietary-algorithms/)
6. [*Soundex*](https://en.wikipedia.org/wiki/Soundex)
7. [*Duplicate Detection, Record Linkage, and Identity Uncertainty: Datasets*](https://www.cs.utexas.edu/users/ml/riddle/data.html)
