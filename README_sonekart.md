# Sonekart v3 TEST – 32 soner

Testversjon basert på [Sonekart-ColliXL-v2](https://mikkelnikolaievensen.github.io/Sonekart-ColliXL-v2/).
v2-repoet er urørt.

## Endringer fra v2
- **Sone 6 utvidet** med Nøtterøy, Tjøme og Hvasser: 3120, 3121, 3128 Nøtterøy,
  3132 Husøysund, 3133 Duken, 3135 Torød, 3138 Skallestad, 3140 Nøtterøy,
  3142 Vestskogen, 3143 Kjøpmannskjær, 3145 Tjøme, 3148 Hvasser.
  Alle Tønsberg-postnummer med gateadresse ligger nå i sone 6.
- **Holdt utenfor:** 3144 Veierland (øy uten veiforbindelse, kun ferje).
  Postboksnummer (kategori P) er ikke lagt til, som ellers i kartet.
- **Sone 19 delt i tre:**
  - 19 Hamar/Ringsaker/Gjøvik – uendret pris (ledd 5 fra sone 10)
  - 31 Hadeland (Lunner, Gran, Brandbu, Jaren, Harestua, Grua, Roa, Grindvoll) – ledd 3 fra sone 10
  - 32 Stange/Toten (Stange, Tangen, Espa, Romedal, Vallset, Åsvang, Raufoss, Reinsvoll, Eina, Bøverbru) – ledd 4 fra sone 10
  - Trafikk mellom 19, 31 og 32 er på laveste ledd (som Østfold-splitten).
  - Sone 31 og 32 arver kjøredag tirsdag fra sone 19.
- Priser: `Prismatrise_10.11.26_32_soner_v11_Alletjenester.xlsx`, alle 21 tjenester.

## Innhold
- Postnummer: 1145 · Soner: 32 · Flater: 1206
- Uten flate: 1393, 1520, 1521, 1522, 1527 (postboks-/serviceområder)
- Nye flater er hentet fra Kartverkets `Basisdata_0000_Norge_25833_Postnummeromrader`
  (EPSG:25833 → WGS84).
