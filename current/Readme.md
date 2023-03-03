# Denne mappe indeholder aktuelle masters og mappings


## Listeformatets kolonner:
### FromLevel / ToLevel
- Benyttes til at mappe mellem klassifikationer ordnet i træstrukturer med flere lag. Mappes til en flad klassifikation uden lag benyttes 0 i Level kolonnen. Der benyttes 0 for klassfikationens øverste lag / hovedgrupper. 
- Eksempelvis SfB's hovedgruppe 1-8, der mappes med level = 0, bygningsdele (10, 20, 30 etc) mappes med level 1 mv.

### FromCode / ToCode
- Beskriver klassifikationens entydige kode.
- Eksempelvis SfB's hovedgruppe 1, bygningsdel 10 og 

### FromName_da / ToName_da
- Beskriver navnet for en given klassifikation på dansk.

### FromName_en / ToName_en
- Beskriver navnet for en given klassifikation på engelsk.

### FromProperty_PropertyName / ToProperty_PropertyName
Benyttes til at kunne mappe mellem klassifikationer, hvor der er 'en-til-mange' relationer mellem FromCode og ToCode, men hvor mange-relationen eksisterer fordi der inden for samme FromCode er variationer.
Eksempelvis ved SfB's bygningsdele, hvor der udover en "generel" kategori også findes en række materiale-variationer, der mapper til forskellige BOSSINF klassifikationer.


