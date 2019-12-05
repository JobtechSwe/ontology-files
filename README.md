Temporary Ontology files v0.02 2019-12-05
====================================

termer_koncept_yrke.csv - yrkestitlar (arbetsgivarnas beskrivning från platsannonstexter, ej yrken enligt https://www.scb.se/dokumentation/klassifikationer-och-standarder/standard-for-svensk-yrkesklassificering-ssyk/ ) /job title terms  
termer_koncept_kompetens.csv - kompetensord/competences  
termer_koncept_formaga.csv - förmågor/soft skills  

Beskrivning av kolumner
-----------------------------
term;uuid;concept;type;term_uuid;term_misspelled;version  

term - term in lowercaseuuid - unique id for concept ( this id will be replaced when the Ontology is merged with the Jobtech Taxonomy)  

concept - preferred term for the concept. Many terms can refer to the same concept.  

term_uuid - unique id for term  

term_misspelled - True if the term is misspelled, points to the same concept as at least one correctly spelled term  

version - build version of the ontology files for download  
