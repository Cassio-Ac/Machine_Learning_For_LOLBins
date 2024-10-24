# Machine_Learning_For_LOLBins

This repository hosts the Jupyter notebooks used in my research articles developed at the University of Brasília (UnB). My goal is to make these codes accessible to support researchers and students in replicating, studying, and building upon the work presented in my papers.


## Related Work 

Many academic works present key concepts without providing access to the underlying source code. To enable deeper analysis and practical experimentation, some of these works have been reimplemented in Python.

- [Ongun](0_Ongun_Cmd2Vec.ipynb); 

A crucial reference for my thesis was the Master’s thesis by [Thuy Ngan](https://researchportal.unamur.be/en/studentTheses/classification-of-linux-commands-in-ssh-session-by-risk-levels), which focused on classifying Linux commands by risk levels in SSH sessions.

```
@MastersThesis{Ngan2020,
  author     = {Ngan, D. Thuy},
  school     = {University of Namur, Faculty of Computer Science},
  title      = {Classification of Linux Commands in SSH Session by Risk Levels},
  year       = {2020},
  month      = {September},
  note       = {Student thesis: Master in Computer Science with Professional focus in Data Science},
}

```

## First Paper - 2024 - Iberian Conference on Information Systems and Technologies (CISTI)

> Once the paper is published on IEEE, I will provide the link here.

Living Off the Land Binaries (LOLBins) is a cyber intrusion technique in which the attacker exploits legitimate operating system binaries to carry out criminal actions. This work proposes to compare different machine learning techniques to automatically detect LOLBins attacks. The command lines were preprocessed  using Natural Language Processing (NLP) algorithms. The effectiveness of the methods was evaluated taking into consideration data balancing techniques such as Random Oversampler/Undersampler and SMOTE. Performance metrics such as accuracy and F1-Score were used to compare the different techniques. In conclusion, it was verified that the Decision Tree (DT) and Random Forest (RF) algorithms were superior to the others. Furthermore, using a command window as input generated better results than evaluating isolated command lines.

### Notebooks: 

- [Bag Of Words](1_ARTIGO_BoW.ipynb); 
- [Doc 2 Vec](1_ARTIGO_Doc2Vec.ipynb); 
- [TF-IDF](1_ARTIGO_TFIDF.ipynb);
- [First Results](1_Resultados.ipynb); 
- [Second Results - With Grade](1_Testes_resultados.ipynb)


