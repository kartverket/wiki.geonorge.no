---
layout: default
title: Tilgang & passord
nav_order: 2
has_children: true
permalink: /docs/tilgang
---

# Tilgang & passord

De fleste datasett og tjenester i Norge defineres som åpne data. Disse er markert med en åpen grønn hengelås i kartkatalogen, og et filter kan aktiveres for å kun vise åpne data.

Dataene er som regel underlagt lisenser for åpen bruk. De mest brukte lisensene er NLOD (Norsk lisens for offentlige data) og CC (Creative Common). Lisensene regulerer hvordan data kan brukes og hvem som kan bruke dem, men gir stor frihet til bruk både offentlig og kommersielt. Åpne data kan lastes ned gratis og uten passord.

## Data med regulert tilgang

Noen data og tjenester er underlagt adgangsbegrensing, og disse er ikke tilgjengelig uten nærmere avtale. Det finnes to typer av slike data:

- Data som inneholder skjermet informasjon. Lover og forskrifter beskriver hvem som kan få tilgang og hva dataene kan brukes til. Eksempler på slike er matrikkelloven med forskrifter, sikkerhetsloven, personopplysningsloven og offentlighetsloven.
- Datasett det må betales for er regulert gjennom egne avtaler. Norge digitalt-parter kan få tilgang gjennom sin Norge digitalt-avtale, mens private virksomheter kan få det gjennom egne avtaler med dataeiere.

Bruksbegrensinger kan også foreligge selv om de ikke er hjemlet i lov. Dette er beskrevet i metadataene for datasett og tjenester i kartkatalogen.

Data med regulert tilgang er beskyttet av Kartverkets tilgangssystem GeoID, eller i dataeiers egne løsninger.

## BAAT og GeoID - brukernavn og passord

GeoID-tilgang brukes for å få adgang til tilgangsbegrensede data, og for å legge inn informasjon som metadata, kodelister og så videre. Hvis du har en BAAT-tilgang i dag, må du overføre brukeren din til GeoID. Dette gjør du enkelt ved å følge anvisningene du får når du prøver å logge på Geonorge. Etter at du har gjort dette, vil det være passordet du oppretter i GeoID som skal brukes ved pålogging på websidene i Geonorge. Det stilles strengere krav til passord i den nye løsningen og passordet må byttes ut minst en gang hvert år. BAAT-brukeren din vil ikke slettes, men vil brukes videre som før i andre systemer som fremdeles bruker BAAT-pålogging (for eksempel tilgang til WMS-tjenester). For nedlastning av tilgangsbegrensede data via «Geonorge - massiv klient» (egen installerbar applikasjon), gjelder dagens brukernavn og passord (basic authentication) som før, og du som bruker trenger ikke gjøre noen endringer. Det samme gjelder for de som programmerer direkte mot Geonorge nedlastnings-API.

GeoID-tilgang gis bare til parter i Norge digitalt-samarbeidet. Samarbeidet består av [nasjonale](https://www.geonorge.no/globalassets/geonorge2/parter/nasjonale-parter-i-norge-digitalt-1.pdf) og [regionale parter](https://www.geonorge.no/globalassets/geonorge2/parter/regionale-parter-i-norge-digitalt.pdf).

Parter kan søke om brukernavn og passord ved hjelp av vårt [registreringsskjema](http://www.geonorge.no/NDUserForm/).

Bruk av data og tjenester tilgjengelig gjennom Geonorge samt Geonorges tjenester, brukernavn og passord utover det som er avtalt, medfører tap av tilgang. Parten plikter å sette seg inn i og følge restriksjoner gitt i lover, forskrifter og inngåtte avtaler.

[Det gjelder spesielle vilkår for undervisningssteder i Norge digitalt](https://www.geonorge.no/Geodataarbeid/Norge-digitalt/studenter-og-undervisningssteder/).

[Her er liste over ansvarlige personer på undervisningssteder](https://www.geonorge.no/globalassets/geonorge2/parter/nasjonale-parter-i-norge-digitalt-1.pdf).

### Tilgang til matrikkelinformasjon

Norge digitalt-parter som skal ha tilgang til matrikkeldata med matrikkelens API, benytter søknadsskjemaet (se lenger ned på siden). Alle med avtale om tilgang til matrikkeldata kan få tilgang til innsynstjenester, endringslogg og rapporter fra Matrikkel API i tillegg til WFS og WMS, men det krever brukernavn og passord i matrikkelen.

Dersom partene skal ta i bruk annen matrikkelinformasjon enn det som er beskrevet i [Forskrift om utlevering, viderebruk og annen behandling av opplysninger fra grunnboken og matrikkelen §3, 2.ledd](https://lovdata.no/dokument/SF/forskrift/2013-12-18-1599?q=matrikkellov), må det dokumenteres at partens bruk kommer under en av hjemlene for utlevering etter [Lov om eigedomsregistrering § 30, 1. og 2.ledd](https://lovdata.no/dokument/NL/lov/2005-06-17-101).

Partene er selv ansvarlig for å sende melding om bruk til Datatilsynet når dette er påkrevet etter personopplysningsloven. Slik melding skal sendes minst 30 dager før data tas i bruk. Hvis melding eller konsesjon er påkrevet for partens behandling, skal kopi av melding eller konsesjon legges ved, ref. matrikkellovens forskrift §12, 2.ledd.

Norge digitalt-parter som skal ha tilgang til matrikkelinformasjon beskrevet i matrikkelloven §30, 3.ledd og utleveringsforskriften §3, 2.ledd, trenger ikke dokumentere bruk. Dette er data (adresse, bygningspunkt og eiendomskart) som også fritt kan lastes ned fra Geonorge.no eller vises i et digitalt kart. Da med fra 15 minutter til en ukes forsinkelse, les metadata i [Geonorges kartkatalog](https://kartkatalog.geonorge.no/?type=dataset&type=series&type=service&organization=Kartverket&dataaccess=Det%20er%20ingen%20begrensninger%20p%C3%A5%20tilgang%20til%20datasett%20og%20tjenester&theme=Eiendom).

[Les mer om tilgang til eiendomsinformasjon](https://kartverket.no/api-og-data/eiendomsdata).

[Søk om tilgang til matrikkelinformasjon](https://kartverket.no/api-og-data/eiendomsdata/soknad-api-tilgang).

[Les mer om skjermingsverdige bygningstyper](https://www.kartverket.no/eiendom/bygninger/skjermingsverdige-bygningstyper).

[Les mer om standardvilkår for interkommunale selskapers bruk av personnummer (pdf)](https://www.geonorge.no/globalassets/geonorge2/diverse-filer-norge-digitalt/interkommunaleselskaperogbehovfortilgangtilpersonnummerimatrikkelen.pdf).

### Forhandlere av kartdata

Brukere som ikke er part i Norge digitalt kan kjøpe data hos forhandlere. Se [oversikten over forhandlere av kartdata hos kartverket.no](http://www.kartverket.no/Bestille/Bestille-kartdata/).

### Spørsmål

For spørsmål, eller hjelp til utfylling av skjemaene, bruk e-post: [post@norgedigitalt.no](mailto:post@norgedigitalt.no) eller telefon 32 11 80 00.
