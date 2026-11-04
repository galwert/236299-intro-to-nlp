# 236299 Introduction to Natural Language Processing (Technion)

Four project segments in PyTorch, each a self-contained executed notebook with
its rendered PDF. All use the ATIS flight-query domain where relevant.

| Folder | Project | Methods |
|---|---|---|
| `project1-text-classification/` | Text classification | Majority baseline, naive Bayes, logistic regression, MLP |
| `project2-sequence-labeling/` | Slot filling as sequence labeling | HMM baseline, BiLSTM tagger, span-level evaluation |
| `project3-cky-parsing/` | Constituency parsing | Context-free grammar for ATIS, CKY recognition and parsing, PCFG best parse |
| `project4-semantic-parsing/` | Semantic interpretation for question answering | Logical-form grammar over the CKY parser, execution against a flight database |

```bash
pip install -r project1-text-classification/requirements.txt
jupyter notebook project1-text-classification/project1_classification.ipynb
```
