# SfB_2_BOSSINF mapping

## Om
- Mapping fra SfB til BOSSINF støttekategorier.
- Der er taget udgangspunkt i mapping fra LCCbyg.

## Kilde
- LCCbyg nøgletal for bygningsdele version 3.4

## Bemærkninger
- Der er i denne version mappet mellem "alment"-variationen af en SfB-bygningsdel og BOSSINF.
- Under hver "alment" kategori findes der dog flere materiale-variationer. Ved nogle materiale-variationer mappes til forskellige BOSSINF-koder. Disse variationer i mapping er ikke medtaget i denne version. Ved mapping til hver materiale-variation kan FromProperty_PropertyName benyttes til at specificere variationen, der er nødvendigt for at kunne mappe unikt for x.xx SfB-koderne.
  - Eksempel:
    - 5.52 Afløb og sanitet - Primært tegl => Afløb i jord og bygninger (BOSSINF)
    - 5.52 Afløb og sanitet - Primært metal alment => Tekniske anlæg (BOSSINF)
    - 5.52 Afløb og sanitet - Primært kobber => Tag (BOSSINF)

## Licens
- ?
