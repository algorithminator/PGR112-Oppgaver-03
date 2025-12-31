# Oppgavesett 03

---

## Info

> For å jobbe med oppgavene, skal du plassere koden din i denne `assignment`-mappen. For å teste koden din, finner du testoppsett
i mappen `test/java/assignment/TestAssignment.java`. Der kan du velge å kjøre alle tester samtidig eller kjøre dem en og en.
> 
> Husk å commite koden din hyppig og pushe den opp i GitHub når du f.e. sitte fast og ønsker feedback av
> gruppen din eller student assistene. 
> 
> Når du føler at du ferdig med oppgavene, selv om du ikke klarer å løse alt,
> push gjerne til GitHub. Det ville gi oss lærere en bedre oversikt over klassens 
> progresjon.
> 
> Lykke til!

---

## Oppgave #1

Denne oppgaven finner du i Canvas, hvor oppgaven går ut på å bli kjent med IntelliJ.

---

## Oppgave #2

I denne oppgaven skal du lage en klasse som heter _Book_ - denne kommer vi til å ta i bruk senere i emnet.

- Lag en klasse med navnet _Book_ som i første utgangspunkt skal ha 3 felter:
    - _title_
    - _author_
    - _numberOfPages_

- Velg en datatype som kan passe for hver av disse feltene

---

## Oppgave #3

- Lag en konstruktør inne i _Book_-klassen med følgende parametere:
    - _title_, _author_ og _numberOfPages_

- Konstruktøren skal sette disse verdiene som den mottar og lagre disse i feltene vi opprettet i oppgave #2


---

## Oppgave #4
- Lag en metode _printInfo_ inn i _Book_-klassen som
  skriver ut (via _System.out.printf_ eller _IO.print_ om du foretrekker) tilstanden til objektet –
  altså printer ut verdiene i feltene i en linje
  "Tittel: _title_, Forfatter: _author_, Antall sider: _numberOfPages_"
  til terminalen: Vær nøyaktig med formattering for ellers feiler testene senere.


---

## Oppgave #5
- Opprett en ny (kompakt)klasse som heter _JavaProgram_
    - Inne i denne klassen, opprett en main-metode som gjør følgende:
        - Oppretter én instans av av klassen _Book_ ved bruk av new-nøkkelordet
        - Via denne instansen (objekt av type _Book_), kall på metoden du lagde i oppgave #4

---

### Oppgave #6
- Opprett en ny klasse som heter _Books_ og som er i utgangspunkt en kopi av 
klasse _Book_ med samme felt, konstruktør og metode som du har lagret i oggavene #2 til #4.
- Inne i _Books_-klassen, lag gettere og settere for alle feltene.
- Sørg for at alle feltene i _Book_-klassen er private.

---

## Oppgave #7

- Her skal du gjøre noe nytt: Husker du hvordan du opprettet en ny klasse via «New»-
  menyen?
    - Her skal du lage en ny klasse som heter _Genre_, men, istedenfor å velge «Class» i listen under hvor du skriver inn navnet på klassen, velg «Enum» istedenfor.
        - I filen som opprettes, i kodeblokken til klassen, mellom `{` og `}`, her skriver du en komma-separert liste med følgende verdier:
            - CRIME, ACTION, FANTASY, CLASSIC, OTHER
            - Og eventuelt andre sjangere for bøker du kan komme på.

---

## Oppgave #8

- Lag et nytt felt i _Books_-klassen med navnet _genre_ som er av type _Genre_.
- Lag getter og setter for dette nylige opprettede feltet.

---

## Oppgave #9

- Legg til en til konstruktøre til _Books_-klassen med _genre_ som et av parametrene
og gjør nødvendige endringer.
- Det er svært viktig at du beholde din første konstruktør for at testing av tidligerer oppgaver ikke feiler. 

---

## Mengdetrening

- Finn deg et annet konsept enn en «Book» - dette kan være alt fra en bil, sykkel, vannflaske, fjernsyn, lyspære, lommebok osv. – prøv gjerne å finn noe du interesserer deg for eller kan mye om, og som ikke er veldig komplisert

- I en ny mappe, f.e. `assignment/ekstra/`, gjør de samme oppgaver over tilpasset til din klasse – her må du finne felter som er relevant og riktige datatyper til dem, og et par metoder som gir mening å ha.


---

## Annen informasjon

Det oppfordres til å kode på engelsk, og kommentarer på norsk eller engelsk.

Med disse oppgavene (+ mengdetreningen) er det meningen å bruke tid på, og det forventes at du er helt ferdig med alle disse oppgavene til forelesning 07 starter.