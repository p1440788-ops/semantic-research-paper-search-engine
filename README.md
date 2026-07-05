# semantic-research-paper-search-engine
### Semantic Research Paper Search Engine

An NLP-powered semantic search engine that retrieves research papers based on semantic similarity instead of exact keyword matching.

### Features

* Semantic Search using Sentence Transformers

* Fast retrieval using FAISS

* Keyword Extraction using KeyBERT

* Named Entity Recognition (NER) using spaCy

* Transformer-based Text Summarization

* Similarity score ranking

* Research paper title and abstract visualization

### Technologies Used

* Python

* Pandas

* NumPy

* Sentence Transformers

* FAISS

* KeyBERT

* spaCy

* Hugging Face Transformers

* Scikit-learn

* Jupyter Notebook

### Project Workflow

Dataset

Text Cleaning

Sentence Embedding Generation

FAISS Index Creation

User Query

Semantic Search

Keyword Extraction

Named Entity Recognition (NER)

Text Summarization

Display Results

### NER Implementation

The project implements Named Entity Recognition (NER) using spaCy's en_core_web_sm model.

Recognized entity types:

* PERSON

* ORG

* GPE

* LOC

* DATE

* PRODUCT

* EVENT

* WORK_OF_ART

* NORP

* FAC

Note: The current implementation is designed for general English entities. Scientific concepts such as "Deep Learning" and "Medical Imaging" may not always be recognized because they are domain-specific terms rather than standard named entities.

### Example Query

Input

Copy

search_with_keywords_and_entities("Deep Learning in Medical Imaging", k=5)

### Future Improvements

* Integrate SciSpaCy for scientific NER

* Improve keyword ranking

* Add a web-based interface

* Support PDF uploads

* Fine-tune summarization for research papers

### Learning Outcomes

* Semantic Search

* Vector Embeddings

* FAISS Indexing

* Keyword Extraction

* Named Entity Recognition

* Transformer Models

* Text Summarization

