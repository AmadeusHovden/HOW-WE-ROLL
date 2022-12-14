#### OPPGAVER SOM SKAL GJØRES OG NOEN MÅ SVARES PÅ!!!

1) Kartlegge deres kunnskap og ferdigheter om prosjektarbeid så langt (dokument
GR-KUNN-FERD) og beskrive hva er relevant for denne oppgaven (f. eks. bruk av verktøy
som Git og Github i prosjektplanleggingen og gjennomføringen, bruke av
programmeringsverktøy som HTML5, Canvas, CSS, JavaScript osv.).

2) Gjennomføre en analyse basert på “Kravspesifikasjonen” (dokument FS-ANALYSE, hvor
“FS” står for applikasjonsnavnet “Felles-skapet”). I analyse skal det  inngå en beskrivelse av
alle brukerhistorier for deres variant av “Felles-skapet” og en relevant argumentasjon for
eventuelle prioriteringer av disse.

3) Basert på kartleggingen (som er beskrevet i GR-KUNN-FERD dokumentet) og
FS-ANALYSE, beskrive konkrete eksempler for hvordan en prosjektgruppe kan samle inn informasjon om 
prosjektmedlemmene og presentere resultatene (Figur 1 må brukes som
utgangspunkt). WEB-FORM er input og WEB-RAPPORT er output. Bruk skisser for å
illustrere hvordan deres input og output skal se ut.

4) Mellom input og output skal det være FS-SYSTEM, som skal omgjøre input til output. Del
opp hele prosessen fra input til output i FS-SYSTEM-STEG og illustrer med skisser/tekst.
Beskriv datamodellen som dere bruker for databehandling (f. eks. hvordan dere navngir
attributter i HTML elementer, selektorer i stilark og navn og variabler i JavaScript;
navngiving skal følge konvensjoner og kravspesifikasjoner for det aktuelle
rammeverkene/verktøyene og være konsistent gjennom applikasjonene).

5) Velg funksjoner (JavaScript)/fragmenter av markup-språket (HTML)/stilark (CSS), som
eksisterer i de gitte rammeverkene, som egner seg for hvert steg i FS-SYSTEM-STEG. Alle
funksjoner må dokumenteres (enten i kommentarer i koden, eller i dokumenter i deres Github
repository).

6) Foreslå tester for hvert av stegene og implementer funksjoner for hvert steg ved å kontinuerlig
bevise at funksjonene tilfredsstiller testene. Dokumentert i FS-TESTER.

7) Berører punktene 1) til 6): Lag eget prosjekt for oppgaven, velg bord eller tabell i Github og
beskriv måten dere bruker Github for dokumentasjon og samarbeid under deres arbeid med
oppgaven. Reflekter over samarbeidet.


#### SVAR:

1) 
Etter flaggoppgaven har gruppen bygd en viss forståelse av hvordan man skal drive et prosjektarbeid. Det var litt vanskelig å jobbe som et prosjekt i en så liten oppgave. De fleste av gruppen føler de har mer å lære og oppleve innenfor prosjektarbeid, noe forhåpentligvis HWR-oppgaven vil bidra med. Men vi har alle bygd en liten kunnskap og har lært noe nytt og nyttig som vi vil ta i bruk på HWR-oppgaven. Av dette kan Kanban Board nevnes, som var nytt for flere av oss. Dette ser vi nå som et viktig hjelpemiddel som det er nyttig å mestre. Vi har så vidt fått brukt det og må derfor bygge litt mer kunnskap rundt smartere bruk, slik at vi kan fordele oppgaver på best mulig måte i HWR. 

De fleste av oss hadde heller ikke erfaring med programmering. Etter prosjektet har vi fortsatt mye å lære når det kommer til HTML, CSS, Canvas, og JavaScript. Et par på gruppen hadde drevet med dette før. Så en kombinasjon av hjelp fra disse, samt jevn deltagelse på flaggoppgaven gjorde at vi begynte å forstå hvordan programmering fungerte og hva det kunne brukes til i denne oppgaven. For å fullføre HWR-oppgaven har vi satt oss som mål å jobbe mye på egen hånd, slik at alle får en god nok forståelse til å gjennomføre. 

2) 
Brukerhistorie Survey og Rapport.
For å kartlegge gruppearbeidet, tenkte gruppen det var lurt å lage en survey for å innhente informasjon og en rapport som fremviste resultatene. Dette for å optimalisere og tilpasse gruppearbeidet til oss medlemmer. Bestillingen fra how we roll var å inkludere arbeids-preferanser i surveyen. Gruppen syns dette var litt lite informasjon og vi hadde lyst til å inkludere en til funksjon for å hente mer informasjon om hverandre. Derfor kom vi fram til at vi ville inkludere personlighetstrekk som kunne implementeres ved bruk av «checkboxes», samt et tekstbidrag ved å bruke «textboks»,der man kunne forklare hva en hadde jobbet med før og eventuell erfaring tidligere prosjekter. Slik kunne vi få en større verdi ut av surveyen og kunne bruke denne informasjonen til å kartlegge videre arbeid med prosjektet (EnTur, u.å).

Brukerhistorie Kalender.
Planlegging av gruppearbeid var ikke alltid like lett, og kontrollen på ulike innleveringer kunne gå i surr. Gruppen så et behov som møtte løses. Derfor kom gruppen fram til ideen om en kalender. Denne skulle hjelpe gruppen med å holde orden på arbeidet, frister og kunne brukes til planlegging av gruppemøter. Dette kunne gi oss en stor verdi og ville være til stor hjelp hos gruppen. For å implementerer dette, måtte medlemmene finne løsninger og funksjoner som kunne gjøre denne til realitet via progarmmeringen. Dette var en veldig god ide, men vi var usikre på om dette kunne fullføres med vårt kompetansenivå (EnTur, u.å).

Brukerhistorie Design.
Prosjektmandatet var at gruppen skulle lage en webapplikasjon, der vi skulle fremstå som et konsulentfirma. Av den forstand var det viktig for oss at vår applikasjon skulle bli brukervennlig, være oversiktlig og ha et stylish design. Gruppen skjønte fort at dette ville kreve mer tid, og derfor var det viktig at alle bidro og kom med ideer samt skisser. Skissene til design og oppsett blir vist nedenfor. Gruppen så for seg en meny i header der man kunne navigere seg rundt, som skulle bli viktig i sluttproduktet. 



3) 
En prosjektgruppe kan bruke flere metoder for å hente inn informasjon om hvert enkelt medlem. I HWR skal vi hente inn informasjon om hvert enkelt gruppemedlem slik at vi kan forbedre og spesifisere arbeid. Dette kan gjøres så lett som et kort gruppemøte der vi alle snakker og forklarer hvordan vi liker å jobbe, men dette er ikke veldig oversiktlig og kan være vanskelig å huske. Derfor har vi valgt å gjøre dette via en ‘WEB-FORM’ der vi lager et skjema som hvert medlem kan fylle ut. Da blir dataen lagret ved hjelp av server "bacit.info". Disse svarene skal vi fremvise i en ‘WEB-RAPPORT’. Slik kan gruppen sammenligne hverandre lett og vi kan planlegge gruppemøtene deretter. Vi har også planlagt å gjøre noe litt annerledes i tillegg,  på selve ‘FORMEN’. Eventuelt inkludere noen andre ting som kan være lurt for å bli bedre kjent og planlegge arbeid. Ikke kun ha en form med arbeidspreferanser som: «EARLY BIRD» osv, slik bestillingen fra how we roll antydet 
Skissene vi har laget for å siden vår er veldig varierte og selve siden endte opp med å bli ganske så annerledes, da nye ideer og inspirasjon dukket opp underveis. Skissene blir visst i Sluttrapporten. 


4) og 5) (SLÅ DISSE SAMMEN?)
Kodene er kommentert i selve filene. Elementer og funskjoner som er brukt er kommentert kort ved bruk av kommentar funksjonen. (noe er skrevet på engelsk, da et av gruppemedlemmene forstår dette bedre. Spesielt javascript er skrevet mye engelsk) Dette forklarer hva koden gjør, eller hva den betyr og hva som skjer. Starten av koden på index.html altsp headeren og designet går igjen på alle HTML sidene. Alle 'navn'.html sidene er også helt like og det er kun "amadeus.html" som er kommentert da det samme er tatt i bruk. Koden er godt kommentert i html og css filene. Men her er også en ytterligere forklaring av tankengangen og hva vi har implementert, disse sto opptinnelig i selve koden. Men lange beskrivelser og kommentarer i en kode kan gjøre det veldig uoversiktlig. derfor blir de skrevet her i oppgaveteksten:



Koden til kalender og postitlappene er ikke super kommentert da dette er mye inspirert fra youtube og er ikke noe vi hadde klart på egenhånd. Disse funksjonene er mest med i HWR prosjektet vårt som en god ide til funksjoner et prosjektarbeid burde ha.

6) ....

7) 
Github var et sentralt verktøy og hjelpemiddel i HWR-prosjektet, og gjorde det mulig for alle medlemmene å jobbe sammen via branches. Når noen gjorde endringer på sin personlige branch, brukte vi push- og merge metoden til main branch. Før pull-requests ble godkjent, sjekket vi alltid gjennom endringen. Dette for å forhindre eventuelle feil før de ble lagt inn i main-branch. Når endringer ble godkjent, måtte alle hente de fra main-branch til sin personlige branch ved bruk av pull-metoden. På den måten sørget vi for at alle holdt seg oppdatert kontinuerlig. Github fungerte svært bra for å holde kontroll over programmeringen og forhindre feil. 

I Github Projects brukte vi Kanban Board som en metode for å optimalisere arbeidsflyten. Vi valgte "bord"- som fremviser gjøremål, hva som er i arbeid og hva som er utført. Denne metoden fungerte bra for å få en oversikt over arbeidet, da oppgavenes fremgang ble godt dokumentert via de tre kolonnene. Det gjorde det enklere for gruppen å samarbeide om målet, ettersom det forhindret usikkerhet rundt hva som skulle gjøres. I tillegg unngikk vi at noen jobbet på samme oppgave uten å være klar over det, noe som sannsynligvis har spart oss for mye tid. Arbeidsflyten ble enda bedre da vi fant ut at vi kunne tildele personer oppgaver ved bruk av "tags". På den måten var det alltid sikkert hvem som skulle gjøre hva, og om noen trengte hjelp opprettet vi "issues".

Oppsummert fungerte samarbeidet i gruppen bra, og arbeidsflyten ble optimalisert ved hjelp av Github og bruk av Kanban Board i Github Projects. 

