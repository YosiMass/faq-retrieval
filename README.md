# hrl-faq-retrieval

This package contains paraphrases for the two FAQ datasets (FAQIR and StackFAQ) used in the ACL'20 paper  
paper "Unsupervised FAQ Retrieval with Question Generation and BERT"

Those paraphrases have passed the filter as described in the paper. 

Each file is a tsv format, where each line contains two fields 

- The original question from the FAQ
- A paraphrase

For example 

```How do I delete my Facebook account? \t What can Facebook do to permanently delete my Facebook account?```

If you use the data please include citations to the following paper:

```
Yosi Mass, Boaz Carmeli, Haggai Roitman, David Konopnicki, 2020,
Unsupervised FAQ Retrieval with Question Generation and BERT,
in proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, July 5-10
```
