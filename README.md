# Legal NER

## Overview

This project focuses on identifying 14 different types of legal entities within the Indian Judicial Dataset. We employ a multi-pronged approach, leveraging cutting-edge models like DeBERTa and ELECTRA, as well as utilizing Zero-shot and One-shot Named Entity Recognition (NER).

## Dataset

We used the Indian Legal NER Dataset (Prathamesh Kalamkar, 2022), which is a corpus of 46,545 annotated legal named entities mapped to 14 legal entity types. The dataset is extracted from Preamble and Judgement documents of the Indian judicial system. 

## Approach

- **Fine-tuning Advanced BERT Models**: DeBERTa and ELECTRA
- **Zero-shot and One-shot Learning**: Transforming multi-class token classification into binary token classification
- **Prompt Engineering**: Used GPT 3.5 and experimented with zero-shot, one-shot, and few-shot learning scenarios.
- **Baseline**: Spacy NER component pipeline

Detailed report along with results are summarized [here](https://github.com/Samitkk18/legal-NER/blob/main/Final_Report_CSE256.pdf).


## Acknowledgements

This is a group project done as a part of a graduate UCSD course [Statistical Natural Language Processing](https://cseweb.ucsd.edu/~nnakashole/teaching/256_sp19.html).
