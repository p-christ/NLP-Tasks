![BERT](miscellaneous/BERT.png)  ![TF2.0](miscellaneous/tf2.0.png) ![Transformer](miscellaneous/transformer.png)



# NLP-Tasks
             
This repository provides simple notebooks that achieve high scores (~top 1%) in various NLP competitions using TensorFlow 2.0. All notebooks
can be run on Google colab in under 1 hour. 

## 1. Offensive Language Classification ([Codalab](https://competitions.codalab.org/competitions/20011))
We fine-tune a pre-trained BERT model to achieve scores that would have won the competition. See `notebooks/Codalab_Offensive_Language_Competition_ipynb`

## 2. Toxic Comment Classification ([Kaggle](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/rules))
We implement a simple model for this task using Glove word embeddings and a bidirectional GRU that achieves a score 
 that would have put us roughly in the top 1\% of Kaggle submissions for this competition. See `notebooks/Toxic_Comment_Classification_(Kaggle)_Simple_Baseline.ipynb` 


3rd could be Emo context... https://competitions.codalab.org/competitions/19790#learn_the_details