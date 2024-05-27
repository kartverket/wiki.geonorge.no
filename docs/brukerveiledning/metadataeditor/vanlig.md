---
layout: default
title: Metadataeditor - Vanlig
parent: Metadataeditor
nav_order: 1
---

# Metadataeditor

Veileder for etablering og bruk av metadataeditoren i Geonorge

**Tittel:** Veileder for metadata  
**Utarbeidet av:** Norge digitalt  
**Søkeord:** Veileder, metadataeditor, NSDI, SDI, Infrastruktur for stedfestet informasjon, Norge digitalt.  
**Opplagstall:** 1 elektronisk  
**Versjon:** 20220111  
**Dato:** 11.01.2022  
**Dok. status:** Arbeidsversjon

## Metadataveileder

### Versjon 1.5

**Utgiver:**  
Kartverket 2022.  
Veilederen utgis av Kartverket som nasjonal geodatakoordinator.

### Revisjonshistorikk

| Versjon  | Produsert av | Dato       | Endring          |
| -------- | ------------ | ---------- | ---------------- |
| 20220111 | Kartverket   | 2022-01-11 | Første versjon.  |

### Innholdsfortegnelse

1. [Innledning](#innledning)
   - [Formål](#formål)
   - [Målgruppe](#målgruppe)
   - [Hvordan skrive gode metadata](#hvordan-skrive-gode-metadata)
2. [Finne metadataeditoren og opprette metadata](#finne-metadataeditoren-og-opprette-metadata)
   - [Opprette metadataoppføring](#opprette-metadataoppføring)
   - [Enkle metadata](#enkle-metadata)
   - [Batch-oppdatering](#batch-oppdatering)
   - [Oppbygning av editeringsverktøyet](#oppbygning-av-editeringsverktøyet)
   - [Lagring](#lagring)
   - [Hjelpetekster](#hjelpetekster)
   - [Obligatoriske metadata](#obligatoriske-metadata)
   - [Engelsk metadata](#engelsk-metadata)
3. [Fane Grunnleggende](#fane-grunnleggende)
   - [Tittel (Påkrevd)](#tittel-påkrevd)
   - [Beskrivelse (Påkrevd)](#beskrivelse-påkrevd)
   - [Hjelp for bruk](#hjelp-for-bruk)
   - [URL til hjelp](#url-til-hjelp)
   - [Bruksområde (Påkrevd)](#bruksområde-påkrevd)
   - [Formål (Påkrevd)](#formål-påkrevd)
4. [Fane Tid og rom](#fane-tid-og-rom)
   - [Dato sist oppdatert](#dato-sist-oppdatert)
   - [Publiseringsdato](#publiseringsdato)
   - [Opprettet dato](#opprettet-dato)
   - [Gyldig fra dato](#gyldig-fra-dato)
   - [Gyldig til dato](#gyldig-til-dato)
   - [Oppdateringshyppighet (Påkrevd)](#oppdateringshyppighet-påkrevd)
   - [Spatial scope](#spatial-scope)
   - [Nøkkelord for geografisk område](#nøkkelord-for-geografisk-område)
   - [Nøkkelord for administrative enheter](#nøkkelord-for-administrative-enheter)
   - [Geografisk utstrekning](#geografisk-utstrekning)
   - [Dekningskart](#dekningskart)
     - [Bildefil](#bildefil)
     - [Karttjenestelag](#karttjenestelag)
     - [Webside](#webside)
     - [Dekningskart Geonorge](#dekningskart-geonorge)
5. [Fane Kontaktinformasjon](#fane-kontaktinformasjon)
   - [Metadatakontakt](#metadatakontakt)
   - [Teknisk kontakt](#teknisk-kontakt)
   - [Faglig kontakt](#faglig-kontakt)
6. [Fane Distribusjon](#fane-distribusjon)
   - [Representasjonsform](#representasjonsform)
   - [Distribusjon](#distribusjon)
     - [Organisasjon](#organisasjon)
     - [Distribusjonstype](#distribusjonstype)
     - [URL](#url)
     - [Formater](#formater)
   - [Romlig referansesystem](#romlig-referansesystem)
7. [Fane Dokumentasjon](#fane-dokumentasjon)
   - [SOSI produktspesifikasjon](#sosi-produktspesifikasjon)
   - [UML-modell](#uml-modell)
   - [Begreper](#begreper)
   - [Annen produktspesifikasjon](#annen-produktspesifikasjon)
   - [Produktark](#produktark)
   - [Tegneregler](#tegneregler)
   - [Produktside](#produktside)
   - [Illustrasjonsbilde (Påkrevd)](#illustrasjonsbilde-påkrevd)
8. [Fane Restriksjoner](#fane-restriksjoner)
   - [Bruksbegrensninger](#bruksbegrensninger)
   - [Tilgangsrestriksjoner](#tilgangsrestriksjoner)
   - [Brukerrestriksjoner](#brukerrestriksjoner)
   - [Andre restriksjoner](#andre-restriksjoner)
   - [Sikkerhetsnivå](#sikkerhetsnivå)
   - [Lovhenvisning](#lovhenvisning)
9. [Fane Nøkkelord](#fane-nøkkelord)
   - [Tematisk hovedkategori](#tematisk-hovedkategori)
   - [Tema](#tema)
   - [Nasjonal temakategori](#nasjonal-temakategori)
   - [Inspire-kategorier](#inspire-kategorier)
   - [EU-prioriterte datasett](#eu-prioriterte-datasett)
   - [Ukategoriserte nøkkelord](#ukategoriserte-nøkkelord)
10. [Fane Kvalitet](#fane-kvalitet)
    - [Målestokktall](#målestokktall)
    - [Status](#status)
    - [Prosesshistorie](#prosesshistorie)
11. [Fane Administrativt](#fane-administrativt)

---

## Innledning

### Formål

- Gi oversikt over metadataeditoren i Geonorge og innholdet i denne
- Gi oversikt over hvordan man kan legge inn metadata

### Målgruppe

Etater og offentlige enheter med behov for å registrere metadata i Geonorge

### Hvordan skrive gode metadata

Informasjonen i metadataoppføringen bør være informativ og konsis. Det anbefales å se gjennom dokumentet Bedre metadata før man etablerer metadata.

## Finne metadataeditoren og opprette metadata

Opprettelse av nye metadataoppføringer i Geonorge gjøres ved hjelp av metadataeditoren. For å komme til denne kan man gå direkte til <https://editor.geonorge.no> eller navigere seg fram i menyen på Geonorge. Velg meny og verktøy.

Siden Verktøy vil åpnes. Bla nedover til du finner Metadataeditor og trykk på denne. Du vil nå komme til metadataeditoren.

For å kunne opprette metadata må man være logget inn. Dette gjøres ved å gå til Meny og trykke Logg inn. Her må man logge inn med brukernavn og passord. Har man ikke brukernavn og passord kan man henvende seg til post@norgedigitalt.no. Er du allerede logget inn i Geonorge vil du komme rett inn i editoren.

## Opprette metadataoppføring

Metadataeditoren er inndelt i flere faner. Den første fanen viser en oversikt over sin etats etablerte metadata. For å opprette metadata trykker man på fanen Opprett metadata. Fyll deretter inn tittel på metadataoppføringen, velg type, skriv inn navn og e-postadresse til metadatakontakt. Trykk deretter på knappen Opprett metadata for opprette metadata.

### Enkle metadata

Metadataeditoren har en egen fane for enkle metadata. Denne viser en forenklet versjon av metadataeditoren, hvor kun utvalgte metadatafelt er tilgjengelig. Det vil kunne være fordelaktig å benytte standard metadataeditor som dette dokumentet beskriver, da standard metadataeditor gir flere muligheter for metadatainformasjon. Gjennomgang av enkel metadataeditor finnes i dokumentet enkel metadataeditor.

### Batch-oppdatering

Fanen batch-oppdatering gir tilgang til funksjoner for å massivt oppdatere metadatafelt i en enkel operasjon. Det anbefales at du tar kontakt med Geodatakoordinator på post@norgedigitalt.no hvis du har metadata som ønskes massivoppdatert.

## Oppbygning av editeringsverktøyet

Du har nå opprettet metadataoppføringen og har kommet til delen av metadataeditoren hvor man legger inn selve metadataene. Editeringsverktøyet er delt inn i flere faner med gruppert informasjon.

## Lagring

Endringer og informasjon lagt til i editoren lagres ved å trykke på knappen Lagre nederst på siden.

Ved lagring vil du umiddelbart få tilbakemelding om eventuelle manglende informasjon gjennom feilmeldinger over arkfanene. Du vil også få rød markering på arkfane og markering på hvilket påkrevd felt som mangler. Du vil imidlertid likevel kunne lagre metadataene dine dersom du huker av for «Ignorer feil» like ved lagre-knappen. Dette kan være nyttig for å lagre stegvis i prosessen for å hindre at metadata mistes.

## Hjelpetekster

Samtlige felter i metadataeditoren har til høyre for seg, en knapp formet som et spørsmålstegn. Ved å trykke på denne knappen vil du få opp en hjelpetekst for hva det aktuelle feltet skal inneholde.

## Obligatoriske metadata

Felter i metadataeditoren som er obligatoriske og må fylles ut mer merket med rød stjerne *

## Engelsk metadata

Alle tekstfelt har mulighet for å legge til engelsk tekst. Ved et tekstfelt kan man velge å vise feltet hvor man skriver inn norsk, engelsk, eller vise begge samtidig.

## Fane Grunnleggende

### Tittel (Påkrevd)

Datasettnavn bør være presist og entydig og definere et unikt datasett. Generelle begreper bør unngås, slik at ulike etater som har samme type data ikke vil oppgi samme datasettnavn. Eksempelvis bør «Lokaliteter» unngås. Her bruker vi «Akvakulturlokaliteter» og «Kulturminner - Lokaliteter». Videre unngås datasettnavnet «Støy», da det er flere produsenter av støydata. Her brukes «Støy - bane», «Støy - veg», «Støy - lufthavn» og «Støy - skytebane».

### Beskrivelse (Påkrevd)

Beskrivelsen er det første brukerne møter etter tittel og skal være utdypende til denne. Gi brukeren oversikt over datasettet ved å sette den viktigste informasjonen først. I beskrivelsen bør du fokusere på hva datasettet eller tjenesten inneholder. Feltet er obligatorisk for alle oppføringer.

### Hjelp for bruk

Formålet med hjelp er å tilby kort og grunnleggende informasjon om hvordan dataene skal tas i bruk. Eksempelvis kan man informere om hvilket filformat man skal velge, eller hvilken programvare som egner seg for å lese og bruke dataene. Under hjelp har man også mulighet til å legge inn lenke til dataeiers egen hjelpeside hvis dette skulle forekomme.

### URL til hjelp

Finnes egen ekstern hjelpeside kan lenke til denne legges inn her.

### Bruksområde (Påkrevd)

Oppgi hvilke oppgaver datasettet kan, og eventuelt bør, brukes til. For datasett som inngår i det offentlige kartgrunnlaget (DOK) bør det spesielt henvises til bruksområder som er relatert til kommunenes plan- og byggesaksarbeid. Bruksbegrensninger skal fylles inn under bruksbegrensninger i fanen Restriksjoner

### Formål (Påkrevd)

Formål skal informere om det formålet dataene ble samlet inn for. Det skal også her informeres hvis dataene ikke egner seg til annet bruk enn det formålet de ble samlet inn for.

## Fane Tid og rom

### Dato sist oppdatert

Dato for siste oppdatering av datasettet/tjeneste. Oppdateres dataene kontinuerlig, holder det å angi tidspunkt for etablering av datasettet/tjenesten i feltet Opprettet dato.

### Publiseringsdato

Datoen referer til første publikasjon av datasettet/datasettet.

### Opprettet dato

Datoen referer til dato for opprettelse av datasettet/tjenesten

### Gyldig fra dato

Angi dato hvis datasettet/tjenesten først er gyldig fra en gitt dato

### Gyldig til dato

Angi dato hvis datasettet/tjenesten er gyldig til en gitt dato.

### Oppdateringshyppighet (Påkrevd)

Angir intervall for oppdateringer av datasettet/tjenesten. Valg gjøres fra nedtrekksliste.

### Spatial scope

Spatial scope omtaltes i filteret i kartkatalogen i Geonorge som dekningsområde og angir dekningsområde for datasettet. Velges fra nedtrekksliste.

### Nøkkelord for geografisk område

Nøkkelord for geografisk område kan angis som tekst og vil være søkbart. Administrative inndelinger som fylke og kommune legges inn i nøkkelord for administrative enheter. Legg til flere nøkkelord ved å trykke på knappen Legg til nøkkelord.

### Nøkkelord for administrative enheter

Velg administrativ enhet som passer for datasettet. Denne kan være fylke, kommune eller Norge (landsdekkende). Legg til flere nøkkelord ved å trykke på knappen Legg til nøkkelord.

### Geografisk utstrekning

Geografisk utstrekning viser datasettets utstrekning i form av koordinater. For å angi koordinater kan man velge landsdekkende, fylket eller kommunen datasettet dekker. Man kan også angi dette ved å tegne rektangel i kart, eller skrive inn koordinatene. Velger du fra nedtrekksliste eller ved å tegne rektangel vil dette sette inn koordinatene for deg.

### Dekningskart

Dekningskart kan angis som egen webside, lag i en visningstjeneste eller bildefil.

#### Bildefil

Du kan laste opp en bildefil fra egen datamaskin som viser dekningsområdet for dataene dine ved å trykke «velg fil» og deretter «last opp» når du har valgt filen.

#### Karttjenestelag

Du kan angi en karttjeneste som har et lag som viser dekningsområdet.

#### Webside

Du kan lenke til en webside eller PDF som er tilgjengelig på internett som viser utbredelsen av dataene.

#### Dekningskart Geonorge

Datasett som går gjennom Geonorges distribusjonsløype vil få generert eget dekningskart og er angitt som «Dekningskart Geonorge». Geodatakoordinator tar i noen tilfeller på seg å sette opp distribusjon av data på vegne av dataeier, og omtales her som Geonorges distribusjonsløype.

## Fane Kontaktinformasjon

Det er kun påkrevd å angi e-postadresse og organisasjon for kontaktpunkt. Det anbefales likevel å legge til navn. Organisasjonsnavn hentes fra organisasjonsregisteret i Geonorge.

### Metadatakontakt

Metadatakontakt er den som vedlikeholder metadata og kan svare på spørsmål knyttet til disse.

### Teknisk kontakt

Kontaktpunkt som kan svare på tekniske detaljer om publisering og tilgjengeliggjøring av dataene.

### Faglig kontakt

Kontaktpunkt som har et eierforhold til dataene og kan svare inngående om faglige forhold rundt datasettets struktur og innhold.

## Fane Distribusjon

I fanen distribusjon angis det hvordan datasettet distribueres, hvem som distribuerer dette, endepunkt og distribusjonsformater.

Ved enkelte anledninger kan man benytte flere distribusjoner. Dette er eksempelvis aktuelt hvis data distribueres både gjennom Geonorges distribusjonsløype, men også direkte fra dataeier. Er det usikkerhet rundt flere distribusjoner anbefales det å ta kontakt med post@norgedigitalt.no. Finnes dataene både som vektor- og rasterfiler må det opprettes to metadataoppføringer.

### Representasjonsform

Velg representasjonsform fra nedtrekksliste.

### Distribusjon

#### Organisasjon

Angi organisasjonen som distribuerer datasettet/tjenesten.

#### Distribusjonstype

Velg type distribusjon fra nedtrekksliste. Her velger man hvordan ressursen distribueres, eksempelvis som filnedlasting eller tjeneste. Er du usikker på hva du skal velge kan du sende epost til post@norgedigitalt.no for hjelp.

#### URL

Her legges adressen til nedlastingsside eller tjenesten inn.

### Formater

Format som ressursen distribueres i velges fra nedtrekksliste. Valgmulighetene i nedtrekkslisten er gitt på bakgrunn av valgt representasjonsrom. Velger man vektor som representasjonsform vil man få andre formater å velge mellom enn hvis man velger raster.

### Romlig referansesystem

I dette feltet kan man angi aktuelle referansesystem ressursen distribueres i. Aktuelle referansesystemer angis ved valg i nedtrekksliste. Man kan legge til flere referansesystemer ved å trykke på knappen Nytt referansesystem.

## Fane Dokumentasjon

### SOSI produktspesifikasjon

Er det etablert en produktspesifikasjon som er tilgjengelig i Geonorges register over produktspesifikasjoner kan denne velges fra nedtrekkslisten.

### UML-modell

Har du valgt en produktspesifikasjon som er koblet til en UML-modell i feltet over, vil dette feltet oppdatere seg automatisk. Er det ikke opprettet koblinger mellom produktspesifikasjonen og UML-modellen, men det foreligger en UML-modell i Geonorges modellregister er det mulig å legge lenke til UML-modellen i modellregisteret her. Ta kontakt med post@norgedigitalt.no for spørsmål og råd.

### Begreper

En UML-modell inneholder informasjon om objekttyper, datatyper og kodelister. Denne informasjonen er mulig å hente fra UML-modellen. Fordelen med å gjøre dette er at denne informasjonen vil kunne bli søkbar i Geonorges søkefelt og forbedre søk som gjøres her. For å hente begreper fra UML-modell må det ligge en lenke til modellen i modellregisteret. Deretter trykker man på knappen Hent.

### Annen produktspesifikasjon

Eksisterer det en produktspesifikasjon som ikke ligger i Geonorge er det mulig å hente inn denne og legge den til i dette feltet. Her legger man inn navn på produktspesifikasjonen og lenke til dokumentet i feltet URL.

### Produktark

Eksisterer det et produktark i registeret i Geonorge vil det være mulig å koble opp dette i metadataoppføringen med å velge produktarket fra nedtrekkslisten.

### Tegneregler

Eksisterer det tegneregler i registeret i Geonorge vil det være mulig å koble disse opp mot metadataoppføringen ved å velge tegnereglene fra nedtrekkslisten.

### Produktside

Finnes det en egen side med informasjon om ressursen kan lenke til denne legges inn i dette feltet. Dette vil aktivere knappen Vis produktside i metadataoppføringen.

### Illustrasjonsbilde (Påkrevd)

Illustrasjonbilde legges til ved å laste opp bilde fra egen datamaskin. Trykk Velg fil for å velge fil på din egen datamaskin. Trykk deretter på knappen Last opp. Bildet vil vises under knappene etter opplasting.

## Fane Restriksjoner

Her er det mulighet for å angi begrensninger og restriksjoner knyttet til tilgang og bruk av datasettet. Det er ikke gjort en grundig vurdering angående hva som er «best practice» på dette området i Norge digitalt.

### Bruksbegrensninger

I dette feltet angir man hvilke områder dataene ikke er egnet for eller hvis det foreligger begrensninger på bruk av dataene. Det anbefales å oppgi hvorfor det er begrensninger på bruk.

### Tilgangsrestriksjoner

Her kan man angi tilgangsrestriksjon fra nedtrekksliste. Valgmulighetene er:

- Åpne data: Data som er åpent tilgjengelig for nedlasting og bruk
- Norge digitalt-begrenset: Data om kun er fritt tilgjengelig for deltakere i Norge digitalt-samarbeidet.
- Skjermede data: Data som ikke er åpne for nedlasting eller begrenset gjennom Norge digitalt-samarbeidet. Dataeier bør se på hvordan brukere skal få tak i skjermede data. Det finnes i dag ulike løsninger på dette hvor dataeier gir tilgang til brukere gjennom dataeiers nedlastingsløsning, eller at det er gitt tilgang gjennom Geonorges autentisering- og nedlastingsløsning.

### Brukerrestriksjoner

Foreligger det brukerrestriksjoner i form av lisens, angis dette i nedtrekkslisten. Velger man Lisens her vil feltet Lisens aktiveres. Man kan da angi aktuell lisens fra nedtrekksliste. Ønsker man å bruke lisenser utover hva som ligger i listen kan man trykke på knappen Egendefinert for å legge dette til.

### Andre restriksjoner

Er det andre restriksjoner på bruk av ressursen kan man legge det til i dette feltet.

### Sikkerhetsnivå

Her kan man angi aktuelt sikkerhetsnivå fra nedtrekksliste.

### Lovhenvisning

Feltet er aktuelt for grunngiving av tilgangsbegrensninger eller bruksbegrensninger i form av juridiske forhold eller andre begrensende faktorer. Her kan en henvise til lov, forskrift eller lignende.

## Fane Nøkkelord

### Tematisk hovedkategori

Her kan man velge tematiske kategorier definert i metadatastandarden.

### Tema

Her kan man angi nøkkelord som vil hjelpe til med å forbedre søket i søkemotoren i Geonorge. Gode nøkkelord er en forutsetning for at metadataene skal bli funnet av brukerne. Nøkkelord skrives i entall og det skal brukes folkelige termer i tillegg til mer spesifikke faguttrykk. Det er ikke nødvendig å gjenta tittel eller organisasjon som eier datasettet. Trykk på knappen Legg til nøkkelord for å legge til flere nøkkelord.

### Nasjonal temakategori

Nasjonal temakategori er en norsk tematisk inndeling basert på kategoriene fra det offentlige kartgrunnlaget. Velg temakategori fra nedtrekksliste. Trykk på Legg til nøkkelord hvis det er aktuelt med flere temakategorier.

### Inspire-kategorier

Hvis datasettet inneholder data som inngår blant Inspire-datasett skal det angis aktuelt tema her. Dette velges i nedtrekksliste. Trykk på Legg til nøkkelord for å legge til kategori.

### EU-prioriterte datasett

Feltet er kun aktuelt for datasett som skal inngå i INSPIREs miljørapportering. Trykk på Legg til nøkkelord for å legge til kategori.

### Ukategoriserte nøkkelord

Ukategoriserte nøkkelord henger igjen fra en tidligere versjon av metadataeditoren og bør ikke brukes. Det anbefales å legge til nøkkelord under Tema.

## Fane Kvalitet

### Målestokktall

Angi målestokktall som heltall. Eksempel 50000.

### Status

Angi status for datasettet/tjenesten fra nedtrekksliste. Dette gir ikke status for metadata.

### Prosesshistorie

Her angis produsentens generelle kunnskap om opprinnelse og prosesshistorie til datasettet eller tjenesten. Her kan det kort forklares viktige operasjoner som er gjort fra datafangst til leveranse og hvordan dette eventuelt påvirker kvalitet og innhold i datasettet.

## Fane Administrativt

Fanen administrativt administreres i stor grad av geodatakoordinator i Kartverket. Man har imidlertid mulighet for å legge til ulike høstinger og samarbeid som datasettet eller tjenesten inngår i. Dette velges fra nedtrekksliste.
