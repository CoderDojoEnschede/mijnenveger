# mijnenveger

Mijnenveger is een eenpersoons puzzelspel. Doel van het spel is om de mijnen in het mijnenveld op te ruimen zonder dat je een mijn (bom) laat afgaan. Je enige hulp hierbij is je geluk en de getallen in de naastgelegen velden die aangeven hoeveel bomvelden tegen het gekozen veld aan liggen.

Het spel is overgenomen van https://iq.opengenus.org/minesweeper-game-using-js/. Bij dit spel op deze website is geen licentie vermelding gevonden. Daarom menen wij dat we de code vrij mogen gebruiken en dat anderen ook vrij gebruik kunnen maken van het afgeleide werk wat wij hebben gedaan op deze code.

Licentie: CC0 1.0 Universal. Je mag deze code overal gebruiken, in je eigen projecten of om er geld mee te verdienen. Er is geen enkele verplichting om te verwijzen naar deze pagina of Coderdojo Enschede, maar het wordt wel gewaardeerd.

Structuur:
index.html {de startpagina}  
mijnenveger.css {de opmaak voor mijnenveger}  
images/mijnenvegerX_Y.png|jpg {images *}  
mijnenveger.js {de benodigde JavaScript code}  

\* Uitgezonderd de Trinket afbeelding is voor afbeeldingen de naamconventie mijnenvegerX_Y.png gebruikt, waarbij X het nummer is uit de naam mijnenveger-opdrachtX en Y is een volgnummer van het image op die pagina.

Opdrachten
0: Trinket werkomgeving instellen **(concept gereed)**

1: HTML/CSS/JavaScript links activeren --> spel zichtbaar
naam spel (Mijnenveger) instellen bovenin de spelpagina met daaronder een horizontale scheidingslijn **(concept gereed)**

**Het spel is nog niet echt fraai**  
2: We klikken zomaar wat rond en er gebeurt wel iets, maar waar moet je klikken en waarom? Geen idee waar vakjes zitten. We tonen daarom randen om de vakjes, zodat het speelveld herkenbaar is. **(concept gereed)**


3: De cijfers zijn allemaal in dezelfde kleur. We veranderen de kleuren voor de cijfers in de css, zodat elk cijfer een eigen kleur krijgt.

4: De bom is nu de letter B. We gebruiken voor de bom een afbeelding i.p.v. de letter B.

5: Het spel stop niet als we op een bom stappen. We zorgen dat het spel eindigt met een melding als er op een bom wordt gestapt.

6: We zijn steeds op F5 drukken zat voor een herstart van het spel en willen een *start nieuw spel* knop

7: We passen het aantal rijen en kolommen aan.

8: We veranderen het aantal bommen in ons spel.

9: We veranderen de veld- en karaktergrootte (css) mits karaktergrootte van bom en getal in de velden hierop passend zijn te maken.

10: We maken een popup venster button met een popup venster met daarin een uitleg van het spel.

Alternatieven in geval een bovenstaande niet lukt
-   de kleur van geflagde velden naar eigen smaak veranderen
-   het spel met de boolean alive manipuleren

Extra opdrachten:  
- 	toevoegen van schermgestuurde instel opties om aantal kolommen, rijen en bommen in te stellen (nu hardcoded in js).
-   teller die afloopt naar 0 met max kliktijd welke speler krijgt om na vorige vak een volgend vak te openen.  
-   oplopende moeilijkheidsgraad inbouwen om na voltooiing spel (of via een levelkeuze) van makkelijk naar moeilijker te gaan (meer velden, meer bommen, kortere kliktijd).  
-   Verfraaiing pagina door (bom) afbeelding of andere verfraaiing op de pagina toe te voegen (bijv in titelgebied)  
