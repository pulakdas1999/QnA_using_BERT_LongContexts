# QnA_using_BERT_LongContexts
BERT, short for Bidirectional Encoder Representations from Transformers, is a machine learning (ML) framework for natural language processing. In 2018, Google developed this algorithm to improve contextual understanding of unlabeled text across a broad range of tasks by learning to predict text that might come before and after (bi-directional) other text. BERT pre-trained models deliver state-of-the-art results in natural language processing (NLP). Unlike directional models that read text sequentially, BERT models look at the surrounding words to understand the context. The models are pre-trained on massive volumes of text to learn relationships, giving them an edge over other techniques. With GPU acceleration in H2O Driverless AI, using state-of-the-art techniques has never been faster or easier.

BERT was specifically trained on Wikipedia (~2.5B words) and Google’s BooksCorpus (~800M words). These large informational datasets contributed to BERT’s deep knowledge not only of the English language but also of our world! 🚀

DistilBERT offers a lighter version of BERT; runs 60% faster while maintaining over 95% of BERT’s performance.

# Masked Language Model Example:

Imagine your friend calls you while camping in Glacier National Park and their service begins to cut out. The last thing you hear before the call drops is:
Friend: “Dang! I’m out fishing and a huge trout just [blank] my line!”
Can you guess what your friend said??
You’re naturally able to predict the missing word by considering the words bidirectionally before and after the missing word as context clues (in addition to your historical knowledge of how fishing works). Did you guess that your friend said, ‘broke’? That’s what we predicted as well but even we humans are error-prone to some of these methods.

# NSP (Next Sentence Prediction) is used to help BERT learn about relationships between sentences by predicting if a given sentence follows the previous sentence or not.
Next Sentence Prediction Example:
Paul went shopping. He bought a new shirt. (correct sentence pair)
Ramona made coffee. Vanilla ice cream cones for sale. (incorrect sentence pair)
In training, 50% correct sentence pairs are mixed in with 50% random sentence pairs to help BERT increase next sentence prediction accuracy.

# Fun Fact: BERT is trained on both MLM (50%) and NSP (50%) at the same time.

![image](https://github.com/user-attachments/assets/8cd26c13-d3c1-4330-97f5-40de2c81be8e)
![image](https://github.com/user-attachments/assets/ceda2f3d-3cec-4a20-a5a6-72072f372e6b)
![image](https://github.com/user-attachments/assets/5f6d258e-7e57-4ee1-a94f-1193edf40151)
