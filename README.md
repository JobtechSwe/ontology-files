README Narval-ontologi
====================================

termer_koncept_yrke.csv - yrkestitlar (arbetsgivarnas beskrivning från platsannonstexter, ej yrken enligt https://www.scb.se/dokumentation/klassifikationer-och-standarder/standard-for-svensk-yrkesklassificering-ssyk/)
termer_koncept_kompetens.csv - kompetensord
termer_koncept_formaga.csv - förmågor

Beskrivning av kolumner
-----------------------------
term;uuid;concept;type;term_uuid;term_misspelled;version

term - term i lowercase
uuid - unikt id för koncept (koncept är gemensamt begrepp för 1 till flera synonymer)
concept - mest lämpliga beskrivningen/ordet för 1 till flera synonymer. Flera termer kan peka på samma koncept.
term_uuid - unikt id för term
term_misspelled - True om termen är felstavad, pekar mot samma koncept som minst en rättstavad variant
version - byggversion av narval-ontologin



