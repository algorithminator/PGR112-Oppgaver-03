# Assignment Text
# Oppgavesett 03

---

> For å jobbe med denne oppgaven, kan du i denne `_03`-mappen opprette en `src`- eller `code`-mappe som kan brukes for å plassere koden din i

---

## Oppgave #1

Denne oppgaven finner du i Canvas, hvor oppgaven går ut på å bli kjent med IntelliJ.

---

## Oppgave #2

I denne oppgaven skal du lage en klasse som heter «Book» - denne kommer vi til å ta i bruk senere i emnet.

- Lag en klasse med navnet «Book» som i første utgangspunkt skal ha 3 felter:
    - title
    - author
    - numberOfPages

- Velg en datatype som kan passe for hver av disse feltene

---

## Oppgave #3

- Lag en konstruktør inne i Book-klassen med følgende parametere:
    - title, author og numberOfPages

- Konstruktøren skal sette disse verdiene som den mottar og lagre disse i feltene vi opprettet i oppgave #2


---

## Oppgave #4
- Lag en metode _printInfo_ inn i Book-klassen som
  skriver ut (via System.out.printf) tilstanden til objektet –
  altså printer ut verdiene i feltene i en linje
  "Tittel: _title_, Forfatter: _author_, Antall sider: _numberOfPages_"
  til terminalen: Vær nøyaktig med formattering for ellers feiler testene senere.


---

## Oppgave #5
- Opprett en ny klasse som heter _JavaProgram_
    - Inne i denne klassen, opprett en main-metode som gjør følgende:
        - Oppretter én instans av av klassen Book ved bruk av new-nøkkelordet
        - Via denne instansen (objekt av type Book), kall på metoden du lagde i oppgave #4

---

### Oppgave #6
- Opprett en ny klasse som heter _Books_ og som er i utgangspunkt en kopi av 
klasse _Book_ med samme felt, konstruktør og metode som du har lagret i oggavene #2 til #4.
- Inne i Books-klassen, lag gettere og settere for alle feltene
- Sørg for at alle feltene i Book-klassen er private

---

## Oppgave #7

- Her skal du gjøre noe nytt: Husker du hvordan du opprettet en ny klasse via «New»-
  menyen?
    - Her skal du lage en ny klasse som heter «Genre», men, istedenfor å velge "Class" i listen under hvor du skriver inn navnet på klassen, velg «Enum» istedenfor.
        - I filen som opprettes, i kodeblokken til klassen, mellom `{` og `}`, her skriver du en komma-separert liste med følgende verdier:
            - CRIME, ACTION, FANTASY, CLASSIC, OTHER
            - Og eventuelt andre sjangere for bøker du kan komme på

---

## Oppgave #8

- Lag et nytt felt i Books-klassen med navnet «genre» som er av type Genre
- Lag getter og setter for dette nylige opprettede feltet

---

## Oppgave #9

- Legg til en til konstruktøre til Books-klassen med genre som et av parameterne og gjør nødvendige endringer

---

## Mengdetrening

- Finn deg et annet konsept enn en «Book» - dette kan være alt fra en bil, sykkel, vannflaske, fjernsyn, lyspære, lommebok osv. – prøv gjerne å finn noe du interesserer deg for eller kan mye om, og som ikke er veldig komplisert
-
- Gjør de samme oppgaver over tilpasset til din klasse – her må du finne felter som er relevant og riktige datatyper til dem, og et par metoder som gir mening å ha

---

## Annen informasjon

Det oppfordres til å kode på engelsk, og kommentarer på norsk eller engelsk.

Med disse oppgavene (+ mengdetreningen) er det meningen å bruke tid på, og det forventes at du er helt ferdig med alle disse oppgavene til forelesning 07 starter.