Copyright 2021 by Nanjing University of Posts and Telecommunication. 

Time: 05/12/2022  Authors:  Qiu Ji & Guilin Qi & Yinkai Yang & Weizhuo Li 

Mail: qiuji@njupt.edu.cn & gqi@seu.edu.cn & lwz@njupt.edu.cn 

Description: Embedding-based Approach to Repairing Incoherent Ontologies


# 1. Introduction:
We focus on dealing with incoherence in ontologies whose axioms can be much more complex than triples. Precisely, we devise an embedding-based approach that translates OWL axioms into natural language sentences and then ranks these axioms employing the embeddings of such translated sentences. We further provide facilities to compute the semantic similarities among axioms. In this way, an axiom in a conflict could 64
be associated with a degree by considering the semantic relationships between the axiom and others. Two algorithms, namely the threshold-based algorithm and the signature-based one, are designed to repair ontologies according to detected conflicts and axiom embeddings. To verify our proposed approach, we compared with existing repair methods over 20 real-life incoherent ontologies.


# 2. Usage:
This project provides the following zip files: 
- incoOntos.zip: 20 real-life incoherent ontologies
- mups.zip: all MIPS of an incoherent ontology has been saved in a log file
- nlp.zip: Provide three files for each ontology. One is the list of sentences corresponding to all axioms in an ontology. One  provides sentence pairs for our algorithm ThrSigAlg. The last one provides sentence pairs, each of which consists of an axiom in a MIPS and an axiom in the ontology.
- similarities1.zip+similarities2.zip: 28 files. Each file contains 20 text files consisting of triples. An triple like (i, j, 0.8) indicates that the similarity between axiom i and axiom j is 0.8.
- repairResults.zip: all experimental results
- resultsAnalyze.zip: All tables and figures
- radon-src02221125: source code of all implemented repair algorithms




