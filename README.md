[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)


# OpenDefender – SnapThreatMap
### Åpne verktøy for digital trygghet, forebygging og innsikt  
**Ingen overvåkning. Ingen identitetssporing. Kun mønstre – aldri mennesker.**

---

## Hva er SnapThreatMap?

SnapThreatMap er et åpent, etisk verktøy som hjelper skoler, kommuner og forebyggende enheter med å forstå **digitale risikoområder** uten å samle inn eller behandle personopplysninger.

Verktøyet viser **risikomønstre**, ikke individer.

Det bygger kun på:

- offentlig tilgjengelige datapunkter  
- anonyme frivillige varsler  
- lokal databehandling (ingen sentral database)  
- et strengt *Privacy by Design*-rammeverk  

SnapThreatMap er første modul i **OpenDefender-initiativet**, et uavhengig samfunnsprosjekt som utvikler åpne verktøy for digital trygghet.

---

## Hvorfor finnes prosjektet?

Barn og unge møter digitale risikoer som utvikler seg raskt. Mange offentlige aktører mangler verktøy som gir:

- oversikt  
- mønsterforståelse  
- tidlige signaler  
- tverrfaglig innsikt  

… uten å kompromittere personvern.

SnapThreatMap gir autoriserte aktører et **rolig, strukturert og transparent** beslutningsgrunnlag basert på **områder og trender** – aldri på enkeltpersoner.

---

## Overordnede mål

- Støtte forebyggende arbeid mot rekruttering, utnyttelse, vold og kriminalitet  
- Tilby åpne, etterprøvbare verktøy for bruk i kommune, skole og politi  
- Sikre at alt arbeid skjer innenfor tydelige etiske og juridiske rammer  
- Gi lokalsamfunn bedre innsikt uten økt overvåkning  

---

## Hva prosjektet *ikke* gjør

SnapThreatMap er **ikke**:

- et overvåkingssystem  
- et etterretningssystem for å følge personer  
- et sporings-, logging- eller profileringsverktøy  
- et ansiktsgjenkjenningssystem  
- en kilde til individdata  

Verktøyet:

- lagrer ingen identiteter  
- analyserer ikke brukeratferd  
- profilerer ingen individer  
- driftes kun lokalt av aktører med lovlig mandat  

---

## Prosjektstruktur

| Fil | Beskrivelse |
|-----|-------------|
| **index.html** | Landingsside – trygg introduksjon til prosjektet |
| **kart.html** | Trusselkart (syntetisk demo med Leaflet) |
| **varsle.html** | Anonym og trygg varslingsside |
| **om.html** | Formål, etikk, rammeverk, mål og prinsipper |
| **pilot.html** | Fullt pilotdashboard med kart, filtrering, tidslinjer, tiltak og DIPD-demo |

---

# DIPD – Desentralisert Incremental Payload Delivery  
### *(Ny modell utviklet i dette prosjektet – ikke tidligere dokumentert i faglitteraturen)*

DIPD er en helt ny teoretisk og teknisk modell utviklet gjennom OpenDefender-arbeidet.  
Modellen beskriver hvordan digitale trusler og påvirkningsprosesser ofte leveres **gradvis**, gjennom:

- fragmenterte datapunkter  
- små mikrointeraksjoner  
- flere plattformer samtidig  
- tid, sekvenser og kombinasjoner  

Enkeltpunkter virker ufarlige – men **kombinasjonen over tid kan utgjøre en risiko**.

DIPD ble utviklet som respons på fenomenet der:

- trusler leveres steg for steg  
- påvirkning bygges opp gjennom sekvenser  
- ungdom rekrutteres eller manipuleres via fragmentert digital kommunikasjon  
- tradisjonelle analyseverktøy ikke fanger opp mønsteret før det er for sent  

Modellen ble utviklet **fra bunnen av** og er per i dag **ikke dokumentert i eksisterende forskning**.

DIPD gir et rammeverk for:

- tidlige varslingssignaler  
- sekvens- og mønsteranalyse  
- tverrplattform-påvirkning  
- forståelse av fragmentert adversarial atferd  

SnapThreatMap inneholder en **forenklet DIPD-light-indikator** i pilotdashboardet.

Et fullstendig fagnotat og whitepaper kommer i en senere versjon.

---

## Pilotdashboard

`pilot.html` demonstrerer hvordan en mulig produksjonsløsning kan se ut:

- kartbaserte digitale risikosoner  
- filtrering på område og kategori  
- visuell utvikling over tid  
- tiltak og faglige observasjoner  
- tidlige varslingssignaler basert på DIPD-light  

All data i dashboardet er **syntetisk** og brukes kun til demonstrasjon.

---

## Etikk og rammeverk

Prosjektet følger prinsipper for:

- **Privacy by Design**  
- **Dataminimering (GDPR)**  
- **Åpenhet og etterprøvbarhet**  
- **Lokal kontroll – ingen sentral database**  
- **Ingen identiteter, ingen profiler, ingen individanalyse**  

---

## Hvem kan bruke SnapThreatMap?

Verktøyet er utviklet for aktører med forebyggende mandat:

- kommuner og deres trygghets- og oppvekstteam  
- skoler og tverrfaglige samarbeidsteam  
- forebyggende politi  
- utekontakt og ungdomsteam  
- forsknings- og fagmiljøer  

---

## Videre utvikling

- publisering av DIPD-whitepaper  
- videreutvikling av demo- og pilotløsninger  
- API-basert backend (FastAPI)  
- tidlige varselmotorer basert på sekvensanalyse  
- tiltak- og samhandlingsmoduler  
- støtte for lokal drift hos kommuner og skoler  
- samarbeid med fagmiljøer og myndigheter  

---

## Bidra

Prosjektet ønsker bidrag innen:

- faglige innspill  
- tekniske forbedringer  
- personvernvurderinger  
- etikk og samfunnsperspektiver  
- samarbeid for pilotering  

Pull requests er velkommen.


> Merk: Kart- og varslingssider er per nå kun demonstrasjoner. All bruk mot reelle data
> skal skje under tydelig mandat, lokal datakontroll og dokumenterte etiske rammer.

## Kontakt

For henvendelser om samarbeid, faglige spørsmål eller utvikling i kommune/skole/politi:

**E-post:** opendefender@proton.me

Henvendelser behandles av prosjektteamet og ikke av enkeltpersoner.
