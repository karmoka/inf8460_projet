# inf8460 Projet : Inférence en langue naturelle

Auteurs :  
- Raphael Croteau
~~- Clément Maurel~~ (N'a finalement rien fait)
- François Vidal (Correction de la langue et début code SRL)

Énoncé :  
- Le but de ce projet est d’indiquer, pour toute paire de phrases dans le corpus, si la seconde phrase contredit, est une conséquence logique ou est neutre par rapport à la première phrase
- Dataset: https://nlp.stanford.edu/projects/snli/  
- Samuel R. Bowman, Gabor Angeli, Christopher Potts, and Christopher D. Manning. 2015. A large annotated corpus for learning natural language inference. In Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing (EMNLP). [pdf]  
- Métriques d’évaluation: nous allons utiliser la mesure générale « Accuracy » qui indique la capacité de votre classifieur à correctement assigner une classe aux paires de phrases.

Input :  
 Document dans le même format que [./snli_test.csv](./snli_test.csv)

Output :  
 Document dans le même format que [./sample_submission_snli.csv](./sample_submission_snli.csv)
