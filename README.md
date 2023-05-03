# Live 3 maj

## Övningar

#### ER-diagram

1. Rita ett ER-diagram för en app åt en biograf. Appens användare ska kunna se vilka filmer som visas för tillfället, hur långa de är och hur många poäng de fått på IMDB.


2. Rita ett ER-diagram för en bokhandelskedja. Entiteter: affär, anställd och bok. Ledning:
    - en affär kan ha flera anställda
    - en affär innehåller flera böcker
    - en anställd jobbar i en affär
    - en bok kan finnas i flera affärer


3. Rita ett ER-diagram för en biblioteksapp. Användarna ska kunna söka efter böcker baserat på titel eller författare.


4. Rita ett ER-diagram för en skola. Skolan har studenter, lärare och kurser.
    - Utöka databasen så att man kan lagra studenters betyg. Tänk på att en del kurser inte har gått än, så det är inte säkert att det finns betyg.


5. Rita ett ER-diagram för en realtidschat. Chatten ska kunna ha flera användare, som skriver meddelanden. Man kan skicka meddelanden direkt till användare.


#### SQL-övningar


1. Visa namnen på alla artister och titlarna på de album de har skrivit.
2. Vilka artister har skrivit ett album, vars titel börjar med "The"?
3. Vilka låtar av Frank Sinatra finns i databasen? 
    <details>
    <summary>Visa tips!</summary>
    Tips 1: ett annat sätt att fråga samma sak är: vilka låtar finns i ett album som Frank Sinatra har skrivit?
        
    Tips 2: du behöver använda två joins.

    </details>

4. Finns det några låtar (track) som inte har en kompositör? (composer=null)
5. Finns det några låtar som inte har en genre?
6. Visa alla låtar som tillhör genren "Latin".
7. Visa alla album som har minst en låt med genren "Latin".
8. Visa alla album som har låtar med genre "Jazz" och "Rock".

9. Vilka låttitlar finns med i spellistan "Grunge"?
10. Vilka artister finns representerade i "Grunge"?
11. Vilka spellistor finns artisten "Led Zeppelin" med på?

