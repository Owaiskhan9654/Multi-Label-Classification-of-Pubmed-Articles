# Multi-Label-Classification-of-Pubmed-Articles
The traditional machine learning models give a lot of pain when we do not have sufficient labeled data for the specific task or domain we care about to train a reliable model.  Transfer learning allows us to deal with these scenarios by leveraging the already existing labeled data of some related task or domain. We try to store this knowledge gained in solving the source task in the source domain and apply it to our problem of interest.  In this work, I have utilized Transfer Learning utilizing BertForSequenceClassification model to fine tune on Pubmed MultiLabel classification Datset.  

Also tried **RobertaForSequenceClassification** and **XLNetForSequenceClassification** models for Fine-Tuning the Model on Pubmed MultiLabel Datset.


<img src="https://raw.githubusercontent.com/Owaiskhan9654/DigiGene/main/Paper%20Night%20Design.gif">


<img src="https://camo.githubusercontent.com/dd842f7b0be57140e68b2ab9cb007992acd131c48284eaf6b1aca758bfea358b/68747470733a2f2f692e696d6775722e636f6d2f52557469567a482e706e67">

> I have integrated Weight and Bias for visualizations and logging artifacts and comparisons of different models!
> 
> Multi Label Classification of PubMed Articles [(Paper Night Presentation)](https://wandb.ai/owaiskhan9515/Multi%20Label%20Classification%20of%20PubMed%20Articles%20(Paper%20Night%20Presentation))


> - To get the API key, create an account in the [website](https://wandb.ai/site) .
> - Use secrets to use API Keys more securely inside Kaggle. 

<img src="https://raw.githubusercontent.com/Owaiskhan9654/Gene-Sequence-Primer-/main/BioAsq.JPG">

For more information on the attributes visit the Kaggle Dataset Description [here](https://www.kaggle.com/datasets/owaiskhan9654/pubmed-multilabel-text-classification).


#### In order to, get a full grasp of what steps should I be taking to utilizing this dataset. Have a Full look at the Dataset and information present in the Kaggle Notebook  [Link](https://www.kaggle.com/code/owaiskhan9654/multi-label-classification-of-pubmed-articles) & Kaggle Dataset [Link](https://www.kaggle.com/datasets/owaiskhan9654/pubmed-multilabel-text-classification)


## <p style="background-color:#1a0a36;font-family:newtimeroman;color:#FFF9ED;font-size:150%;text-align:center;border-radius:10px 10px;"> References</p>
1. [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
2. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
2. https://github.com/google-research/bert
3. https://github.com/huggingface/transformers
4. [BCE WITH LOGITS LOSS Pytorch](https://pytorch.org/docs/stable/generated/torch.nn.BCEWithLogitsLoss.html#torch.nn.BCEWithLogitsLoss)
5. [Transformers for Multi-Label Classification made simple by 
Ronak Patel](https://towardsdatascience.com/transformers-for-multilabel-classification-71a1a0daf5e1)



