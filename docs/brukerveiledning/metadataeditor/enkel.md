---
layout: default
title: Enkel metadataeditor
parent: Metadataeditor
grand_parent: Brukerveiledning
nav_order: 2
permalink: /brukerveiledning/metadataeditor/enkel
---

# Veiledning for Enkel Metadataeditor i Geonorge

Denne veiledningen gir en enkel og kortfattet guide for nye brukere om hvordan man legger inn metadata i Geonorge ved hjelp av den enkle metadataeditoren.

---

#### Innholdsfortegnelse
1. [Opprette enkle metadata](#opprette-enkle-metadata)
2. [Påkrevde felt](#påkrevde-felt)
    - [Navn på datasett](#navn-på-datasett)
    - [Beskrivelse](#beskrivelse)
    - [Dato sist oppdatert](#dato-sist-oppdatert)
    - [Oppdateringshyppighet](#oppdateringshyppighet)
    - [Samarbeid og lover](#samarbeid-og-lover)
    - [Distribusjonstype](#distribusjonstype)
    - [URL til datasett](#url-til-datasett)
    - [Datasett fil](#datasett-fil)
    - [Geografisk utstrekning](#geografisk-utstrekning)
    - [Kontaktinformasjon](#kontaktinformasjon)
3. [Valgfrie felt](#valgfrie-felt)
    - [Bruksområde](#bruksområde)
    - [Supplerende beskrivelse / hjelp](#supplerende-beskrivelse--hjelp)
    - [Prosesshistorie](#prosesshistorie)
    - [Produktside](#produktside)
    - [Lisens](#lisens)
4. [Engelsk](#engelsk)
5. [Lagring og tilgjengeliggjøring av data](#lagring-og-tilgjengeliggjøring-av-data)

---

### Opprette enkle metadata

Enkle metadata oppretter man i metadataeditoren i Geonorge. Denne finner man ved å velge «Verktøy» under menyen og deretter «Metadataeditor». Man kan også gå direkte til editoren ved hjelp av denne adressen: [editor.geonorge.no/Metadata](https://editor.geonorge.no/Metadata). For å komme til metadataeditoren må man logge inn. Ta kontakt med [post@norgedigitalt.no](mailto:post@norgedigitalt.no) hvis du ikke har bruker eller har problemer med å logge inn.

![Skjermbilde av innlogging](path/to/image1.png)


I metadataeditoren trykker man på fanen «Opprett enkle metadata». Her fyller man inn datasettets tittel og trykker deretter på knappen «Opprett metadata».

![Skjermbilde av opprette enkle metadata](https://github.com/kartverket/docs.geonorge.no/assets/22092618/f5722aa5-03f3-49c7-9736-da75ef69663a)


### Påkrevde felt

Når du har opprettet metadata sendes man videre i metadataeditoren. Her kan man fylle ut alle feltene som vil vises for oppføringen i Geonorge. Feltene er delt inn i fanene «Påkrevd», «Valgfritt» og «Engelsk». Alle felt i fanen «Påkrevd» må fylles ut.

![Skjermbilde av påkrevde felt](https://github.com/kartverket/docs.geonorge.no/assets/22092618/a5ad423b-191a-4f1c-9f87-0198b83bbc4f)


#### Navn på datasett
Navnet på datasettet er det viktigste feltet. Navnet skal være konsist og beskrivende. Nevn ikke formater, projeksjoner, etat-/kommuenavn eller lignende detaljer i tittelen.

**Best practice:** Bruk spesifikke og beskrivende navn som "Friluftsområder – statlige sikrede" i stedet for generelle navn som "Områder".

#### Beskrivelse
Beskrivelsen skal være utdypende til tittelen. Gi oversikt over datasettet ved å sette den viktigste informasjonen først og fokuser på hva datasettet inneholder. Er datasettet et tilleggsdata til DOK, kan dette nevnes her.

**Best practice:** Start med den viktigste informasjonen og gjør det klart hva datasettet inneholder.

#### Dato sist oppdatert
Angi dato for når datasettet sist ble oppdatert.

**Best practice:** Dette hjelper brukere med å vurdere dataenes aktualitet.

#### Oppdateringshyppighet
Angivelse av intervaller for oppdatering, modifikasjon eller andre endringer av data etter at de er etablert. Oppdateres datasettet uregelmessig kan man velge «Etter behov».

#### Samarbeid og lover
Huk av om datasettet er en del av det offentlige kartgrunnlaget (DOK) og om datasettet er åpent.

#### Distribusjonstype
Her velger man distribusjonstype for datasettet blant forhåndsdefinerte distribusjoner.

- Geonorge nedlasting: Velg denne hvis det er en enkel fil som skal tilgjengeliggjøres. Se delkapittelet «Datasett fil» for hvordan dette gjøres.
- Ingen online tilgang: Velg denne hvis nedlastingsmuligheter foreløpig ikke foreligger.
- Egen nedlastingsside: Velg denne hvis data ikke skal lastes ned fra Geonorge, men fra egen portal.
- Webside: Velg denne hvis oppføringen gjelder for en webside med integrerte kart.

#### URL til datasett
Gjelder oppføringen for egen webside, kartapplikasjon eller at man har egen nedlastingsside for datasettet, fylles det inn i dette feltet.

#### Datasett fil
Her kan man laste opp filen som skal tilgjengeliggjøres i oppføringen. Før fil(er) kan lastes opp må disse komprimeres og pakkes i en .zip-fil. Velg filen på egen datamaskin ved å trykke «Velg fil». Trykk deretter på knappen «Last opp». Filene godkjennes av geodatakoordinator før disse blir tilgjengelig i Geonorge.

#### Geografisk utstrekning
Velg området datasettet dekker ut fra tilgjengelig liste. Denne er delt opp i kommuner, fylker og landsdekkende utstrekning.

#### Kontaktinformasjon
Fyll inn e-post og organisasjon for metadatakontakt, teknisk kontakt og faglig kontakt. E-postadressen kan med fordel være en fellesadresse til organisasjonen eller avdeling i organisasjonen med ansvar for geodata. Mangler organisasjonen i nedtrekkslisten, ta kontakt med geodatakoordinator på [post@norgedigitalt.no](mailto:post@norgedigitalt.no).

---

### Valgfrie felt

Valgfrie metadatafelt er felt som ikke er obligatoriske. Det anbefales likevel å fylle ut valgfrie felt så langt det lar seg gjøre. Dette vil kunne gi brukeren en bedre forståelse av datasettet.

![Skjermbilde av valgfrie felt](https://github.com/kartverket/docs.geonorge.no/assets/22092618/adee0698-0162-45dc-ae9c-2af888e7c89d)


#### Bruksområde
I dette feltet angis hvilke oppgaver datasettet, kan og eventuelt bør brukes til. Er datasettet en del av DOK bør det henvises til bruksområder relatert til plan- og byggesaksarbeid.

#### Supplerende beskrivelse / hjelp
Supplerende beskrivelse har blitt endret til «Hjelp» i vanlig metadataeditor. Hensikten med dette feltet er å tilby kort og grunnleggende informasjon om hvordan dataene kan tas i bruk.

#### Prosesshistorie
Feltet prosesshistorie skal inneholde opprinnelse og historie til datasettet. Her kan det kort forklares hvilke operasjoner som er gjort fra datafangst til leveranse.

#### Produktside
Finnes det en egen informasjonsside om datasettet skal adressen til denne legges inn her. Ved å fylle ut dette feltet aktiveres knappen «produktside» i metadataoppføringen.

#### Lisens
Det finnes ulike lisenser for tilgang og bruk av geografiske data. Disse er listet i nedtrekksmenyen, hvor man kan velge eventuell lisens. Les mer om lisensene her: [register.geonorge.no/metadata-kodelister/lisenser](https://register.geonorge.no/metadata-kodelister/lisenser).

---

### Engelsk

Geonorge får stadig flere engelskspråklige brukere. Det er derfor anbefalt å fylle ut engelske metadata. Engelske metadatafelt er tilgjengelig i fanen «Engelsk» og inneholder feltene «Tittel» og «Bruksområde». Har du fylt inn norske metadata, vil disse vises på siden av de engelske metadatafeltene.

![Skjermbilde av engelske metadatafelt](https://github.com/kartverket/docs.geonorge.no/assets/22092618/d1f58171-d3a6-4421-87c6-6a1338fdaf4d)


---

### Lagring og tilgjengeliggjøring av data

Når metadatafeltene er fylt ut trykker man på knappen «Lagre» nede på siden. En grønn melding vil vises i toppen av editor med teksten «Metadataene ble lagret» som bekrefter dette. Trykk på knappen «Vis i kartkatalogen» for å se hvordan metadataoppføringen ser ut i Geonorge.

![Skjermbilde av lagring](https://github.com/kartverket/docs.geonorge.no/assets/22092618/669d47e5-abd5-4d7d-bb94-35373c267fbe)


Dataene man laster opp i en enkel metadataoppføring i feltet «Datasett fil» må godkjennes av geodatakoordinator før disse blir tilgjengelig i oppføringen i Geonorge. Filene må komprimeres og pakkes i en .zip-fil før disse kan lastes opp.

Har du problemer eller spørsmål underveis? Ta kontakt med [post@norgedigitalt.no](mailto:post@norgedigitalt.no) for hjelp.
