# CSSWiki


### This project releases the data resources in the article:
*Fengkai Liu and John S. Y. Lee (2024).* [CSSWiki: A Chinese Sentence Simplification Dataset with Linguistic and Content Operations](https://aclanthology.org/2024.lrec-main.375.pdf). In *Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)* (pp. 4205-4213).

### Abstract
Sentence Simplification aims to make sentences easier to read and understand. With most effort on corpus development focused on English, the amount of annotated data is limited in Chinese. To address this need, we introduce **CSSWiki, an open-source dataset for Chinese sentence simplification based on Wikipedia**. This dataset contains 1.6k source sentences paired with their simplified versions. Each sentence pair is annotated with operation tags that distinguish between linguistic and content modifications. We analyze differences in annotation scheme and data statistics between CSSWiki and existing datasets. We then report baseline sentence simplification performance on CSSWiki using zero-shot and few-shot approaches with Large Language Models.

### Annotation Scheme
- Linguistic Operation
	- Substitution: synonyms (SubS), hypernyms (SubH), numbers (SubN), pronouns (SubP).
	- Insertion
	- Deletion
	- Syntactic: merging individual clauses within a sentence (SynM), splitting a sentence (SynS), transforming passive voice into active forms (SynV). 
- Content Operation
	- Elaboration (Elab)
	- Condensation (Cond)

*Notes (19 May 2024).* The updated data file **CSSWiki.xls** in this repository also expands the ***Insertion*** and ***Deletion*** operations. 
