**This project is about using deep learning to predict the sentence of formality. Two methods have been implemented: Formality-BERT and Formality-LSTM.**

**Environment setup**
In order to run the python notebooks, you need to set up an anaconda environment with all the depencies installed in the requirements.txt

**Formality-BERT**
Run formality_bert.ipynb to get the results for Formality-BERT.

**Formality-LSTM**
Formality-LSTM is a multimodal that use both bert embeddings and part-of-speech (POS) tags to predict formality. </n>
First, run extract_bert_embedding.ipynb to get bert embeeding for the four genres. The output of this will be saved as numpy files. Since the embedding files are too big, we are not able to push it to github.</n>
Second, run the tokenization_for_formality_lstm.ipynb to generate POS tags. The pre-generated POS tags have been included in this repository.</n>
Third, run formality_lstm.ipynb to get the results of Formality-LSTM

**Citation**
If you would like to use our code for your project, please cite our published paper with the following citation.</n>
C. Li et al., "Deep Formality: Sentence Formality Prediction with Deep Learning," 2022 IEEE 23rd International Conference on Information Reuse and Integration for Data Science (IRI), San Diego, CA, USA, 2022, pp. 1-5, doi: 10.1109/IRI54793.2022.00014.

Paper title:
Deep Formality: Sentence Formality Prediction with Deep Learning.

Link to paper:
https://ieeexplore.ieee.org/abstract/document/9874199


