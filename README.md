# InformationExtraction-Natural-Language-Proceesing
Implementation of Regular Expressions using nltk to retreive Named Entities and Relations between them

The main focus on the information extraction is to identify the Named Entity Recognition(NER)  and Relation between NERs

The system takes the raw text of a document as its input, and generates a list of NERs and relations between the extracted NERs as its output. For example, given a document that indicates that the company Georgia-Pacific is located in Atlanta, it might generate the tuple ([ORG: 'Georgia-Pacific'] 'in' [LOC: 'Atlanta']). 

The IEER corpus of nltk library is marked up for a variety of Named Entities.  For example, the Named Entity classes in IEER include PERSON, LOCATION, ORGANIZATION, DATE and so on. Within NLTK, Named Entities are represented as subtrees within a chunk structure: the class name is treated as node label, while the entity mention itself appears as the leaves of the subtree.
