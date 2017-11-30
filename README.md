# seq2seq-attention-model
An implementation for attention model in Keras for sequence to sequence model.

# Known bugs
 - This implementation is wrong! The attention model is using the future information in order to predict the next word but since we only tested it on known answers to see how the attention can be used as implicit alignment, the result truns to be fine. The bug is fixable. I have other versions of this code but I have no plan in near future to update this repository.
 
 - The dataset I used is not available now because it wasn't my contribution to this experiment. Maybe in future I can add it here. But first I have to ask if I am alowed. But the idea was to have a synthetic data which two languages represent two different syntax for sentence generation. You can generate such dataset on your own and if you want to test on natural language you need a parallel corpora but of course the vocabulary size might be an issue.
 
 
