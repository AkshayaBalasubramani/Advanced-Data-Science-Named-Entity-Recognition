# Named Entity Recognition

### Description
Named Entity Recognition (NER) is a sub-task of information extraction in Natural Language Processing (NLP) that classifies named entities into predefined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, and more. In the realm of NLP, understanding these entities is crucial for many applications, as they often contain the most significant information in a text.    
Named Entity Recognition (NER) serves as a bridge between unstructured text and structured data, enabling machines to sift through vast amounts of textual information and extract nuggets of valuable data in categorized forms. By pinpointing specific entities within a sea of words, NER transforms the way we process and utilize textual data.   

Process:   
The intricacies of NER can be broken down into several steps:   
1.Tokenization. Before identifying entities, the text is split into tokens, which can be words, phrases, or even sentences. For instance, "Steve Jobs co-founded Apple" would be split into tokens like "Steve", "Jobs", "co-founded", "Apple".    
2.Entity identification. Using various linguistic rules or statistical methods, potential named entities are detected. This involves recognizing patterns, such as capitalization in names ("Steve Jobs") or specific formats (like dates).    
3.Entity classification. Once entities are identified, they are categorized into predefined classes such as "Person", "Organization", or "Location". This is often achieved using machine learning models trained on labeled datasets. For our example, "Steve Jobs" would be classified as a "Person" and "Apple" as an "Organization".    
4.Contextual analysis. NER systems often consider the surrounding context to improve accuracy. For instance, in the sentence "Apple released a new iPhone", the context helps the system recognize "Apple" as an organization rather than a fruit.    
5.Post-processing. After initial recognition and classification, post-processing might be applied to refine results. This could involve resolving ambiguities, merging multi-token entities, or using knowledge bases to enhance entity data.   

## Project
The project makes use of Spacy library to perform Named Entity Recgnition.  
The first part of the model identifies the entites that are pretrained.The input is given in the form of a file and the output of the file is obtained as html format that represents the different entities.An output text file containing the output is also stored.
Further training is also done using Custom data for identifiaction of medical terms is done usinf the training data set from Kaggle    
https://www.kaggle.com/datasets/finalepoch/medical-ner

The output screenshots are attached.
