
# User Stories

## Definition of done

- Werkt functioneel
- Peer review gedaan (min. 1 teamlid)
- Voldoet aan acceptatiecriteria & design
- Ge-merged naar main

## User Story 02: Account aanmaken

**Beschrijving**  
Als gebruiker wil ik mij kunnen registreren op de website met mijn e-mailadres en wachtwoord, zodat ik kan inloggen en toegang krijg tot de website.

**Prioriteit**  
Hoog

**Schatting**  
2 dagen

**Acceptatiecriteria**

- In de database worden het e-mailadres, wachtwoord en de naam van de gebruiker opgeslagen  
- Er wordt gecontroleerd of het e-mailadres al bestaat in de database; indien dit het geval is, wordt een foutmelding getoond  
- Het wachtwoord wordt gevalideerd (bijvoorbeeld: minimaal 5 tekens)  
- Het wachtwoord wordt gehasht voordat het in de database wordt opgeslagen  
- Na succesvolle registratie wordt de gebruiker doorgestuurd naar de inlogpagina  

**Auteur**  
Jayven

---

## User Story 04: Inloggen

**Beschrijving**  
Als gebruiker wil ik snel en gemakkelijk kunnen inloggen, zodat ik toegang krijg tot de homepagina.

**Prioriteit**  
Hoogste

**Schatting**  
2 dagen

**Acceptatiecriteria**

- De ingevoerde gegevens worden gevalideerd voor beveiliging  
- Er wordt gecontroleerd of de ingevoerde gegevens overeenkomen met data in de database  
- Na succesvol inloggen wordt de gebruiker doorgestuurd naar de homepagina  
- Bij onjuiste inloggegevens wordt een foutmelding getoond  
- De gebruiker krijgt een sessie na het inloggen  
- Er is een *remember me*-token beschikbaar  
- Er is een maximaal aantal inlogpogingen binnen een bepaalde tijd om brute-force aanvallen te voorkomen  

**Auteur**  
Jayven

---

## User Story 05: Wachtwoord reset functie

**Beschrijving**  
Als gebruiker wil ik mijn wachtwoord kunnen resetten, zodat ik weer toegang krijg tot mijn account wanneer ik mijn wachtwoord ben vergeten.

**Prioriteit**  
Medium

**Schatting**  
3 dagen

**Acceptatiecriteria**

- De gebruiker ontvangt een e-mail met een link om een nieuw wachtwoord in te stellen  
- Het nieuwe wachtwoord vervangt het oude wachtwoord  
- Na het opslaan kan de gebruiker direct inloggen met het nieuwe wachtwoord  

**Auteur**  
Jayven

---

## User Story 09: Premium account

**Beschrijving**  
Als gebruiker wil ik toegang krijgen tot extra functies wanneer ik een premium account heb, zodat ik sneller matches kan krijgen.

**Prioriteit**  
Medium

**Schatting**  
8 dagen

**Acceptatiecriteria**

- Voor nu wordt een premium wachtwoord gebruikt in plaats van een betaalmethode  
- De premiumstatus wordt opgeslagen in de database gekoppeld aan de gebruiker  
- De gebruiker krijgt onbeperkt *winks*  
- De gebruiker krijgt *superwinks*, waarmee een bericht kan worden meegestuurd  
- Premiumfunctionaliteiten worden duidelijk als zodanig weergegeven  
- De premiumstatus is één maand geldig  
- Wanneer niet opnieuw wordt verlengd, vervalt de premiumstatus automatisch  
- Premiumgebruikers kunnen zien wie hen heeft gewinkt  

**Auteur**  
Jayven

---

## User Story 14: Match algoritme

**Beschrijving**  
Als gebruiker wil ik mensen kunnen *winken* die goed bij mij passen op basis van een persoonlijkheidstest, zodat de kans groter is dat ik iemand vind die bij mij past.

**Prioriteit**  
Hoog

**Schatting**  
14 dagen

**Acceptatiecriteria**

- De persoonlijkheidsgegevens van een gebruiker worden opgehaald uit de database  
- Er wordt een JSON-bestand of database gebruikt waarin staat welke persoonlijkheden goed bij elkaar passen  
- Het algoritme vergroot de kans dat gebruikers personen tegenkomen met een bijpassende persoonlijkheid  

**Auteur**  
Jayven
