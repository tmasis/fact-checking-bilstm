# fact-checking-bilstm

For an intro NLP course.  
Written in Python.

Takes downloaded LIAR-PLUS dataset and pretrained 50-dim GloVe embeddings; extracts claim, justification, prior history, and semantic features of claim; and trains BiLSTM to classify each claim either as True or False or as one of 6 truthfulness labels. We wanted to investigate if and to what extent the justification, metadata, and/or feature vector improved performance. 
The BiLSTM architecture is based off of prior work done by Alhindi et al (2018).
