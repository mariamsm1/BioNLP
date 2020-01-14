BioNLP
=======
Repository for student projects within biomedical text mining from Lund University.


# Resources
## NLP libraries 
CoreNLP

contains many of Stanford’s NLP tools

https://stanfordnlp.github.io/CoreNLP/

AllenNLP

NLP library built on PyTorch

https://allennlp.org/

spaCy

https://spacy.io/

scispaCy  

scispaCy is a Python package containing spaCy models for processing biomedical, scientific or clinical text  

https://allenai.github.io/scispacy/

keras

### Tokenizers
NLTK word_tokenize

NLTK regexp_tokenize

Regular expressions tokenizer

spaCy tokenizer

scispaCy tokenizer

keras text_to_word_sequence

### Parsers
Stanford Parser

Klein, D. and Manning, C. (2002). Fast Exact Inference with a Factored Model for Natural Language Parsing. In Advances in Neural Information Processing Systems.

https://nlp.stanford.edu/software/lex-parser.shtml

https://drive.google.com/open?id=1AwzeEIUt0Ar_hBEOLkFPRB_5ZNqCSlPp

Enju Parser

Miyao, Y. and Tsujii, J. (2008). Feature forest models for probabilistic HPSG parsing. Computational Linguistics

https://drive.google.com/open?id=1nZXHlnNiyCM9GeNF0fhKezvUaXzSp1bQ

CCG Parser

https://drive.google.com/open?id=1xCVL5lMF021BuqzX3L6A2RhbRqJYXY8a

Clark, S., & Curran, J. R. (2007). Wide-coverage efficient statistical parsing with CCG and log-linear models. Computational Linguistics, 33(4), 493-552.

## other BioNLP tools
SPECIALIST NLP tools

https://lexsrv3.nlm.nih.gov/Specialist/Home/index.html


GENIA tagger

part-of-speech tagging, shallow parsing, and named entity recognition for biomedical text

https://drive.google.com/file/d/1C6xTYGvkJtFGC5gylkel_Rur761n3vz1/view
 
TaggerOne

https://www.ncbi.nlm.nih.gov/research/bionlp/Tools/taggerone/

Jensen Lab Tagger

https://bitbucket.org/larsjuhljensen/tagger/src/default/

Ab3P 

abbreviation detection tool

Sohn S, Comeau DC, Kim W, Wilbur WJ. (2008) Abbreviation definition identification based on automatic precision estimates. BMC Bioinformatics.  25;9:402. PubMed ID: 1881755

https://drive.google.com/file/d/1nKfgpZ01Qdd_vYm6llYxhZjsadkWM15J/view


## Bioinformatics databases and ontologies (can be used to build dictionaries)
### General & metadatabases

http://obofoundry.org/

BioPortal

http://bioportal.bioontology.org/

UMLS Metathesaurus

https://www.nlm.nih.gov/research/umls/knowledge_sources/metathesaurus/index.html

https://www.ncbi.nlm.nih.gov/books/NBK9684/


### Proteins & Genes
UniprotKB  

To create a dictionary of gene/protein names (contains protein and gene names including synonyms)  

https://www.uniprot.org/

HGNC

Gene Ontology  

Database with known function of genes 

http://geneontology.org/

Protein Ontology

https://proconsortium.org/

Ensembl

NCBI Gene

### Chemicals

CHEBI


PubChem

To create a dictionary of chemicals/drugs (contains small molecules, but also larger molecules such as nucleotides, carbohydrates, lipids, peptides, and chemically-modified macromolecules) 

https://pubchem.ncbi.nlm.nih.gov/

Drugbank

www.drugbank.ca

Database with drugs and known protein targets (including references for the interaction)

RxNorm

provides normalized names for clinical drugs and links its names to many of the drug vocabularies

https://www.nlm.nih.gov/research/umls/rxnorm/index.html

### Diseases & phenotypes

Disease Ontology  

http://disease-ontology.org/

OMIM  

Database with human diseases and known genes

Research Domain Critieria for Mental Health

https://www.nimh.nih.gov/research/research-funded-by-nimh/rdoc/definitions-of-the-rdoc-domains-and-constructs.shtml

### Tissues & Species
Cellosaurus
https://web.expasy.org/cellosaurus/

Cell Ontology

UBERON
anatomical entities; multicellular organisms and life-cycle stages

NCBI Taxonomy

### Pathways & Reactions
KEGG
Database with known protein signalling pathways

Molecular Process Ontology


## Corpora for training and validation  
Pubannotation

public repository of text annotationin  life sciences

http://pubannotation.org/

Corpora in BioC format  

http://bioc.sourceforge.net/

CRAFT

https://github.com/UCDenver-ccp/CRAFT

GeneTag  

also available in BioC format and updated version GeneTag-05  

https://www.ncbi.nlm.nih.gov/pubmed/15960837

Med Mentions

https://github.com/chanzuckerberg/MedMentions





## Biomedical text sources
Pubmed abstracts

Pubmed Central full-length articles

Europe PMC

BioRxiv

Wikipedia


## Shared tasks and conferences within BioNLP
BioNLP Open Shared Tasks (BioNLP-OST) 

continuation of BioNLP Shared Task (BioNLP-ST)series

https://2019.bionlp-ost.org/

BioNLP Shared Task (BioNLP-ST) (2009, 2011, 2013, 2016)

http://2016.bionlp-st.org/

http://2013.bionlp-st.org/

http://2011.bionlp-st.org/

http://www.geniaproject.org/shared-tasks/bionlp-shared-task-2009


ACL-BioNLP2019 Workshop and associated MEDIQA 2019 task

https://sites.google.com/view/mediqa2019

https://aclweb.org/aclwiki/BioNLP_Workshop

BioCreative

https://biocreative.bioinformatics.udel.edu/

BioASQ

http://www.bioasq.org/

List of several conferences with description

https://bionlp.info/bionlp-conferences/



## Other (relevant blogs, discussion forums, etc)  
Devblog with working example code for med-text relations extraction  

https://www.microsoft.com/developerblog/2016/09/13/training-a-classifier-for-relation-extraction-from-medical-literature/

BioStars bioinformatics forum  

https://www.biostars.org/

Link lists with many resources   

https://www2.informatik.hu-berlin.de/~hakenber/links/benchmarks.html

http://www.nactem.ac.uk/software.php

http://www.becalm.eu/NerResources

http://bio.nlplab.org/

https://github.com/sebastianruder/NLP-progress/


