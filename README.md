# NLP-Group34 : Numerical and Temporal Fact Checking

In this git repo, we have added the scripts used for training, evaluating and generation subqueries for various claims against a given evidence corpus. 

The repo is structured as follows : 
1. NLI Models : Scripts for training the various models
2. Eval and IR Scripts :
   1. Evaluating the trained NLI models.
   2. Retrieving and ranking evidence for claims in the QuanTemp dataset.
3. Claim Decomposition :
   1. Train FlanT5 on ClaimDecomp dataset
   2. Subquery generation on the QuanTemp dataset using the trained FlanT5 model.
   3. Training various NLI models on the FlanT5 decomposed QuanTemp dataset.
   4. Subquery generation on the QuanTemp dataset using Llama3.
   5. Training various NLI models on the Llama3 decomposed QuanTemp dataset.