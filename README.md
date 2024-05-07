# Effect of layer depth on Sparse autoencoders

In this repository we study the effect of layer depth on the performance of sparse autoencoders. In particular, we want to investigate the feature representation hypothesis from Olah et al. 

It seems that based on their definition the feature representation hypothesis is true almost by definition. But that would be useless ofcourse. How can we make the hypothesis more precise and useful?

1. Are there holes in feature space that correspond to no features? For this we will need to learn SAE directions for different "meanings" and then check if there are regions in the space where none of these directions lie
2. What are the effects of tokenization? 
3. What are the effects of Cross entropy loss vs MSE loss? 
4. And many more. 

We will use the transforme lens library by Nanda and also vanilla Pytorch hooks to look inside the transformer and the SAE.