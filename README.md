# Intro
Data augmentations play a crucial role in semi-supervised learning. Can introducing a learnable nonlinear transformation between the representation and the contrastive loss substantially improves the quality of the learned representations. Recently, natural language processing models, such as BERT and T5, have shown that it is possible to achieve good results with few class labels by first pretraining on a large unlabeled dataset and then fine-tuning on a smaller labeled dataset. 

SimClr combines semi-supervised and self-supervised training by first learning generic representations of images on an unlabeled dataset, and then fine-tuning with a small amount of labeled images to achieve good performance for a given classification task. But does this technique work when the unlabeled dataset is substantially small. Lets try to implement [SimClr](/semisupervised_simclr.ipynb) using our vision dataset.

# References

https://ai.googleblog.com/2020/04/advancing-self-supervised-and-semi.html

https://keras.io/examples/vision/semisupervised_simclr/

https://www.happywhale.com
