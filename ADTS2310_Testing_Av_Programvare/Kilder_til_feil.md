# Kilder til feil
### Viktig fordi:
* Feil kan være farlig
* Derfor viktig å forstå hvorfor de oppstår

### Dårlig problemforståelse
* Du kan ikke vite om du har levert en god løsning om du ikke forstår problemet godt

* Dette tar tid, og ofte vil tidlig testdesign måtte oppdateres i tråd med den økte problemforståelsen

### Programmering mot bevegelige mål
* dersom kravspek endrer seg - kan dette føre til siste-liten-endringer og ineffektive løsninger, vanskelig vedlikehold og evt feil.

### Kryptisk kode
* Man skriver ikke kode for kompilatoren, men for vedlikeholderen
* Beskrivende navn, logisk flyt, god dokumentasjon og simplisitet sparer tid, penger og energi

### Dårlig fundamentering (spesifikasjon)
* Dersom kravspek ikke er god, blir ikke prosjektet godt
* I ytterste konsekvens løser man ikke det problemet man egentlig prøver å løse

### Å stole på debuggere
* Moderne programmeringsmiljøer har gode verktøy som hjelper deg å skrive korrekt syntaks
* Likevel, må du forstå hva du skriver og hvordan koden fungerer (eller ikke fungerer)

### Behandle symptomer over sykdommen
* Ikke skrive om programmet utelukkende for å bestå tester
* Skriv god kode som løser problemet testen sjekker om det løser (på en god måte)

### Refaktorering
* Smidig utviklings iterative natur gjør at endringer er uungåelig
* Man prøver som regel å forbedre alle aspekter av koden ved refaktorisering:
    1. Beholde funksjonalitet
    2. Forbedre kvalitet
    3. Øke lesbarhet
    4. Gjøre vedlikehold lettere
    5. Avdekke skjulte feil
* Ved sekvensiell utvikling (fossefall), vil det også føre til refaktorisering, dog sjeldnere og med økte konsekvenser

## Løsningen
Ha metoder som avdekker nye feil så snart de oppstår, som regel gjennom *testing*.