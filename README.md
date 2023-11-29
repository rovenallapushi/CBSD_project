This repository contains the project done for Cognitive, Behavioral and social data course. 

Project participiants:

1. ALEJANDRA OLIVIA CRUCES ANDREWS
2. CHELSIE ADELLE RENESSA ROMAIN
3. MARIO ALEJANDRO TAPIA MONTERO
4. ROVENA LLAPUSHI

DATASET:

This dataset is being used in scope of the course project. 


Reference: Capuozzo, P., Lauriola, I., Strapparava, C., Aiolli, F., & Sartori, G. DecOp: A multilingual and multi-
domain corpus for detecting deception in typed text. In Proceedings of the 12th Language Resources and Evaluation Conference, 1423-1430, (2020, May)



Task ideas, summarizing what is already written in the notebook (to be updated, based on prof feedback):

First approach (compare GPT2 base model and small model using Trainer of hugging face vs training proc done by us):

1. add a summary describing the datset and the problem (what is written in the paper)
2. do a diagram of how GPT-X works
3. Model 1 : understand better the model behaviour when uring Trainer method from hugging face (ask the prof if the methodology is right)  Describe the methodology and motivate the choice  ----------------------> assigned to: Rovena
   
3.1 Model 2 :try with smaller model (distil-gpt2)
   
4. we can implement our own train and evaluate method: follow the instructions given here:   https://colab.research.google.com/github/gmihaila/ml_things/blob/master/notebooks/pytorch/gpt2_finetune_classification.ipynb (Model 3 and Model 4, using gpt2 and distil-gpt2)

 5. error analysis  
 6. cognitive interpretation
    
Second approach (compare GPT2 base model and small model vs BERT Base and small model):

1. add a summary describing the datset and the problem (what is written in the paper)
2. do a diagram of how GPT-X works and BERT works
3. Model 1 : GPT2 base model
   
3.1 Model 2 :try with small model (distil-gpt2) 
   
4. Model 3: BERT base model
4.1 Model 4: BERT small model (distil-uncased-bert)

 5. error analysis  
 6. cognitive interpretation
