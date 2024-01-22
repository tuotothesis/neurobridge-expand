# 2023 Spring


## Basics

The Neurobridge Ontology (NO) has terms that are used to identify the research design and data types of scientific papers. It is used in systems that search and return papers based on queries made by scientists. Some of the terms used in the NO are not defined.

**Goal** of this project is to:

(i) identify NO terms used in the labeling of a corpus of papers
\
(ii) determine which have definitions already available
\
(iii) make new definitions for terms not already defined
\
(iv) develop a machine readable form for these definitions (make an **Resource Description Framework/RDF** file)
\
(v) add these definitions to the NeuroBridge system.

The end product of this will be an enhanced version of the NeuroBridge ontology OWL file.  You can store this and any other artifacts in a github repo we can create next semester. 




## Materials

1. Background Knowledge on **Neurobridge**:
      1. The **Neurobridge Ontology (NO)**: [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10406126/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10406126/)
      2. Neurobridge as a data discovery **platform**: [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10500076/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10500076/)


2. Understand **Ontology** with “The Pizza Tutorial”
     1. Google Drive Version: [https://drive.google.com/file/d/1A3Y8T6nIfXQ_UQOpCAr_HFSCwpTqELeP/view](https://drive.google.com/file/d/1A3Y8T6nIfXQ_UQOpCAr_HFSCwpTqELeP/view)
     2. Web Version: (more info with youtube tutorials)[https://www.michaeldebellis.com/post/new-protege-pizza-tutorial](https://www.michaeldebellis.com/post/new-protege-pizza-tutorial)


3. Resource Description Framework/**RDF** data model: [https://cambridgesemantics.com/blog/semantic-university/learn-rdf/](https://cambridgesemantics.com/blog/semantic-university/learn-rdf/)


4. **(To-do)** Download Neurobridge Ontology:  [https://bioportal.bioontology.org/ontologies/NEUROBRG](https://bioportal.bioontology.org/ontologies/NEUROBRG). 

>    Start by looking through the ontology to find which, if any of the terms fail to have meaningful descriptions. For those I would like you **add a description**. There are several ways of doing this but the first thing I would try is to see if there is a **"seeAlso" **line for the concept.  You may be able to find a decent one or two sentence description from that link if it's there. If not you may have to do a **lit search**. Find an appropriate tag and add the description to the concept.  That you will want to do using an editor like Protégé.

5. the editor we would use, OWL/**Protégé** Tutorial
      1. Official website: [https://protege.stanford.edu/](https://protege.stanford.edu/)
      2. Protégé wiki: [https://protegewiki.stanford.edu/wiki/Main_Page](https://protegewiki.stanford.edu/wiki/Main_Page)


## Update - Jan 22, 2024



1. List of Ontologies, search overlapping terms and add them to “rdfs:seeAlso” column
    1. [https://www.nlm.nih.gov/mesh/meshhome.html](https://www.nlm.nih.gov/mesh/meshhome.html)
    2. [https://www.nlm.nih.gov/research/umls/index.html](https://www.nlm.nih.gov/mesh/meshhome.html)
    3. [https://mondo.monarchinitiative.org/](https://mondo.monarchinitiative.org/)
    4. [https://www.ebi.ac.uk/ols4/ontologies/uberon](https://www.ebi.ac.uk/ols4/ontologies/uberon)
2. The PROV Ontology, a model used by NeuroBridge: https://www.w3.org/TR/prov-o/




## Update - Jan 16, 2024


1. Webprotege: [webprotege.stanford.edu](https://webprotege.stanford.edu/)
2. Hands-on tutorials:
      1. [https://cgi.csc.liv.ac.uk/~frank/teaching/comp08/protege_tutorial.pdf](https://cgi.csc.liv.ac.uk/~frank/teaching/comp08/protege_tutorial.pdf)
      2. The People Ontology: 
      3. PizzaTutorialData: [https://drive.google.com/file/d/1oFRBfBNSTQqXAXg_8PYYoB0S44kIW4Y6/view](https://drive.google.com/file/d/1oFRBfBNSTQqXAXg_8PYYoB0S44kIW4Y6/view)
3. Created github repositories for version control: https://github.com/tuotothesis/neurobridge-expand.git
