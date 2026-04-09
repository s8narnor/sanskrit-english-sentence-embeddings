# sanskrit-english-sentence-embeddings
Generate and evaluate cross-lingual sentence embeddings for Sanskrit–English pairs using multilingual transformer models, PCA, and cosine similarity.

**Project Overview**

This project focuses on generating high-quality sentence embeddings for Sanskrit–English parallel text using multilingual transformer models. Sanskrit, being a low-resource and morphologically rich language, presents unique challenges for semantic representation learning.

**Objectives**
- Generate sentence-level embeddings for Sanskrit and English
- Maximize semantic similarity between aligned sentence pairs
- Maintain low embedding dimensionality
- Visualize embedding space using t-SNE

**Models Used**
- paraphrase-multilingual-MiniLM-L12-v2
- LaBSE (Language-agnostic BERT Sentence Embedding)
- DistilUSE Multilingual

**Methodology**
- Data alignment using Source_id
- Sentence embedding generation using transformer models
- Normalization of embeddings
- Dimensionality reduction using PCA
- Evaluation using cosine similarity
- Visualization using t-SNE

**Results**
- Achieved cosine similarity of ~0.46–0.50
- LaBSE showed best cross-lingual alignment
- 256-dimensional embeddings provided optimal trade-off

**Observations**
- Dataset contains some noisy or weakly aligned pairs
- Cross-lingual models still capture moderate semantic similarity
- Dimensionality reduction does not significantly degrade performance


**Conclusion:**

This project demonstrates that multilingual transformer models can effectively generate cross-lingual embeddings even for low-resource languages like Sanskrit, though dataset quality plays a crucial role in performance.
