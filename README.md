# Legal Entity Recognition
[Named Entity Recognition](https://en.wikipedia.org/wiki/Named-entity_recognition)(NER) is a task in the field of information extraction and one of the most common problems to solve in [Natural Language Processing](https://en.wikipedia.org/wiki/Natural_language_processing)(NLP). To goal of NER is to classify named entities such as company names or locations to pre-defined categories. In our use case, legal entities like references to paragraphs or law books are to be extracted within German legal documents. <br>
Unfortunately, pre-trained models are not able to cover such special use cases by default, so we take first steps into fine-tuneing a BERT-model with spaCy v3.0. <br>

## Dataset
    https://github.com/elenanereiss/Legal-Entity-Recognition 

## Requirements
    - SpaCy v3.0
    - de_dep_news_trf model

### References
Leitner, E. (2019). Eigennamen- und Zitaterkennung in Rechtstexten. Bachelor’s thesis, Universität Potsdam, Potsdam, 2.