Temporary Ontology files v0.01 2019-03-22
====================================

termer_koncept_yrke.csv - yrkestitlar (arbetsgivarnas beskrivning från platsannonstexter, ej yrken enligt https://www.scb.se/dokumentation/klassifikationer-och-standarder/standard-for-svensk-yrkesklassificering-ssyk/)
termer_koncept_kompetens.csv - kompetensord
termer_koncept_formaga.csv - förmågor

Beskrivning av kolumner
-----------------------------
term;uuid;concept;type;term_uuid;term_misspelled;version

term - term in lowercase
uuid - unique id for concept ( this id will be replaced when the Ontology is merged with the Jobtech Taxonomy)
concept - preferred term for the concept. Many terms can refer to the same concept.
term_uuid - unikt id för term
term_misspelled - True om termen är felstavad, pekar mot samma koncept som minst en rättstavad variant
version - byggversion av narval-ontologin
