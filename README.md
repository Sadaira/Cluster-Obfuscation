# Cluster Obfuscation
The purpose of this project is to generate text based on cluster-level style and compare it to text generated based on author-level style.


## Data
For my dataset I used the c50 dataset [Reuters dataset]() which includes 5,000 samples and ___ authors. Each author has __ samples.

## Embedding Representation
To embed the text

## Clustering
For cluster obfuscation, I am trying both TF-IDF and graph clustering.

### TF-IDF Clustering

### Graph Clustering

## Finetuning Models
I finetuned LLMs for both classification and text generation.
### Classification Models
For classification, I finetuned three models. The first model was finetuned using the author labels from the dataset while the other two models were finetuned using the TF-IDF and graph cluster labels. The model I finetuned was the mBERT mo
### Text Generation Model
For text generation, I finetuned a T5 model from the Hugging Face platform.


## Results


## Conclusion


## Future Work
I plan on combining several datasets to create a robust dataset that covers multiple types and lengths of documents:
    
- **c50** ()
- **Enron Email Dataset**
- **Brennan Greenstadt**
I would also like to try feeding in real time data from various sources. Maybe utilizing an api from a __ *if clustering shows promise*
I also would like to explore Agentic AI where I would use one agent for classification and another for generation. 

Optimizing the graphs for clustering___

