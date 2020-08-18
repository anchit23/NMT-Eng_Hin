This Neural machine translation project is implemented using a sequence to sequence(seq2seq) model consisting of an Encoder and a Decoder. 
The Encoder encode the complete information of the source language(ENGLISH) into a vector, which is passed to the decoder to produce an output sequence, which is the target language(HINDI)

I have implemented this with Attention Mechanism as it is a better model with more weights to train to give a better prediction. In Attention Mechanism, model pays attention to the specific input vectors of the input sequence based on the attention weights. 

Dataset: Subset of IITB- English Hindi Corpus

Model can be trained on the whole dataset, for more epochs for better accuracy.