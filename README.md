# mijnenveger

Mijnenveger is een eenpersoons puzzelspel. Doel van het spel is om de mijnen in het mijnenveld op te ruimen zonder dat je een mijn (bom) laat afgaan. Je enige hulp hierbij is je geluk en de getallen in de naastgelegen velden die aangeven hoeveel bomvelden aan het gekozen veld liggen.

Het spel is overgenomen van https://iq.opengenus.org/minesweeper-game-using-js/
Bij de versie op hiervoor genoemde website is geen licentie informatie gevonden. Daarom menen wij dat we de code vrij mogen gebruiken en dat anderen ook vrij gebruik kunnen maken van het afgeleide werk wat wij hebben gedaan op deze code.

Licentie: CC0 1.0 Universal. Je mag deze code overal gebruiken, in je eigen projecten of om er geld mee te verdienen. Er is geen enkele verplichting om te verwijzen naar deze pagina of Coderdojo Enschede, maar het wordt wel gewaardeerd.

Structuur:
index.html {de startpagina}
css/mijnenveger.css {de opmaak voor mijnenveger}
images/mijnenvegern_n.png|jpg {images *}
js/mijnenveger.js {de benodigde JavaScript code}

\* Images naamconventie is naamX_Y.extentie, waarbij X is nummer van opdracht en Y is een volgnummer van het image op die pagina.

Opdrachten
0: Trinket werkomgeving instellen

1: HTML/CSS/JavaScript links activeren --> spel zichtbaar
naam spel (Mijnenveger) instellen bovenin de spelpagina met daaronder een horizontale scheidingslijn

Het spel is nog niet echt fraai.
2: We klikken, maar wat, maar geen idee waar velden zitten
We tonen randen om de velden
Uitleg dat het mijnenveld als een tabel is opgebouwd met allemaal vakjes. We zorgen dat er een rand om elk vakje komt.

3: De cijfers zijn allemaal dezelfde kleur
Uitleg over wat de cijfers betekenen
We veranderen de cijfers, zodat elk cijfer een eigen kleur krijgt

4: De B wordt een echte bom
We gebruiken voor de bom een afbeelding ipv een letter

5: Het spel stop niet
We zorgen dat het spel eindigt met een melding als er op een bom wordt gestapt. functie game over

6: we zijn F5 zat en willen een start nieuw spel knop

7: we passen het aantal rijen en kolommen aan

8: we veranderen het aantal bommen in ons spel

9: we veranderen de veldgrootte
(css) mits ook de karaktergrootte bom en getal bomvelden daarmee in overeenstemming zijn te brengen.

10: we maken een popup met daarin een uitleg van het spel

-   de kleur van geflagde velden naar eigen smaak veranderen
-   het spel met de boolean alive manipuleren

Extra opdrachten:  
- 	toevoegen van instel opties in het scherm om aantal kolommen, rijen en bommen in te stellen (nu hardcoded in js).
-   teller die afloopt naar 0 met max tijd welke speler krijgt om na vorige vak een volgend vak te openen.  
-   oplopende moeilijkheid inbouwen bij elke keer dat het spel slaagt of via een levelkeuze (van klein veld of weinig bommen naar steeds groter mijnengebied met meer bommen.  
-   Verfraaiing door bom afbeelding en andere visuele opmaak op de pagina toe te voegen (bijv in titelgebied)  

