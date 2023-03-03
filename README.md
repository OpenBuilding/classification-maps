# Klassifikations mapning

Vi vil forsøge at samle nogle lister med mapning mellem forskellige klassifikationssytemer og typekodninger.

* Forvaltningsklassifikationen, forankret i Landsbyggefonden
* BIMTypeCode, forankret i  http://www.bimtypecode.com/
* CCS/CCI , forankret i Molio
* SfB
* IFC’s bygningselementer og flere andre uformelle systemer.
* BOSSINF


Her er nogle eksempler på de eksisterende tabeller.

https://lbf.dk/publikationer/2014-forvaltnings-klassifikation/

https://view.officeapps.live.com/op/view.aspx?src=http%3A%2F%2Fbim7aa.dk%2FBIM7AA_Typekodning_V3.2.xlsx&wdOrigin=BROWSELINK

https://github.com/bimtypecode/bimtypecode/blob/mapping-table-dk/dk/BIMTypeCode%20-%20Opslagstabel%20-%202022DK.csv


# Mappestruktur

Du finder aktuelle mappinger mellem klassifikationer i mappen "current".
Heri findes mapperne "mappings" og "masters". Mappen "mappings" huser mappings navngivet efter princippet "From_2_To.csv" og ".tsv".
Mappen "masters" indeholder skabeloner for mappings, hvor From-siden er udfyldt og To-siden er blank. Disse findes ligeledes i .csv og .tsv-format.

Tidligere versioner af mappings og masters finder du mappen "archive". Heri findes mapper navngivet med version. I hver af disse findes "mappings" og "master" filer.

Se desuden yderligere information om mappings og master i readme-filer i mapperne.

## Diagram for mappestruktur
- /current/mappings/from_2_to.csv|.tsv
- /current/masters/from_2_x.csv|tsv
- /archive/version/mappings/from_2_to.csv|tsv
- /archive/version/masters/from_2_x.csv|tsv


