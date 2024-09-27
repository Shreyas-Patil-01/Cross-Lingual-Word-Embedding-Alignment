# Cross-Lingual-Word-Embedding-Alignment
 Cross-lingual word embeddings are crucial for various multilingual NLP tasks. This assignment  focuses on aligning monolingual word embeddings from English and Hindi to create a shared  cross-lingual embedding space.
## Implemented a supervised cross-lingual word embedding alignment system for English and Hindi using the Procrustes method.

## Steps:
### 1. Data Preparation:
 a. Training of monolingual FastText word embeddings for English and Hindi using appropriate corpora. Due to computational resources are limited, i used pre-trained FastText embeddings.
 b. Limited vocabulary to the top 100,000 most frequent words in each language.
 c. Extracted a list of word translation pairs from the MUSE dataset to use as a bilingual lexicon for supervised alignment.
 
### 2. Embedding Alignment:
 a. Implemented the Procrustes alignment method to learn a linear mapping between the source (English) and target (Hindi) embeddings using the bilingual lexicon.
 b. Ensured that the mapping is orthogonal to preserve distances and angles between word vectors.
 
### 3. Evaluation:
 a. Performed word translation from English to Hindi using the aligned embeddings.
 b. Evaluated the translation accuracy using the MUSE test dictionary.
 c. Reported Precision@1 and Precision@5 metrics for the word translation task.
 d. Computed cosine similarities between word pairs to assess cross-lingual semantic similarity.

## Images :
![Project Workflow](https://github.com/Shreyas-Patil-01/Cross-Lingual-Word-Embedding-Alignment/blob/main/output_img1%20(1).png)
![Project Workflow](https://github.com/Shreyas-Patil-01/Cross-Lingual-Word-Embedding-Alignment/blob/main/output_img1%20(2).png)

## Any Queries :
 Contact : shreyaspatil4780@gmail.com
