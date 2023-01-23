# Mijnenveger<hr>

Hallo! Jij wilt het spel **Mijnenveger** maken op de computer?

Bij dit spel hebben we niet alles voor je voorbereid. We verwachten van je dat je zelf ook zaken uitzoekt.
Als je hulp nodig hebt, ga je bijvoorbeeld eerst Googlen of je vraagt iemand anders die ook bezig is met het maken van dit spel.
Als je dat al hebt gedaan en nog steeds niet weet hoe je verder moet, dan mag je hulp vragen aan een van de begeleiders.

Elke opdracht hieronder bevat een stukje uitleg en vervolgens zijn er dingen die jij zelf moet doen. Deze dingen staan aangegeven met ▶▶▶

__Aan de slag maar!__


### Opdracht 0: Openen van programmeeromgeving

De code staat in *Trinket*. Dat is een website waarop je kan programmeren en direct het resultaat ziet van wat je hebt aangepast.

▶▶▶ Open Trinket door op de link te klikken: https://trinket.io/embed/html/xxxxxxxxxxxx --> trinket pagina nog toevoegen)

Je moet nu aan de linker kant code zien en aan de rechter kant het nog niet werkende spel Mijnenveger. Als je aan de linker kant de code aanpast, dan verandert de webpagina automatisch na een paar seconden aan de rechterkant.

![](images/afbeelding van Minesweeper in Trinket 0.png)

En nu begint het echte werk!


### Opdracht 1: We willen iets zien!
#### Opdracht 1a: Pagina opmaak en JavaScript

Op de webpagina gebeurt nog niet zoveel. Dat komt omdat de benodigde opmaakcode en JavaScript code nog niet worden gebruikt. De reden daarvan is dat we deze code niet in `index.html` hebben gezet, maar in aparte bestanden hebben geplaatst waar ons spel nog niet bij kan. Dat gaan we veranderen.

Om de code toe te voegen, moeten we een verwijzing opnemen naar de 2  bestanden. De verwijzingen moeten in de *&lt;head&gt;* sectie komen in het bestand `index.html`.

De opmaak code (CSS) staat in het bestand `mijnenveger.css`<br>
De JavaScript code staat in het bestand `mijnenveger.js`

Zoek zelf uit welke instructie nodig is om de beide bestanden op te nemen in het spel. Hint:<br>
- je hebt de tag &lt;link&gt; voor het opmaak (css) bestand  
- je hebt de tag &lt;script&gt; nodig voor het JavaScript bestand  

Probeer eerst zelf het antwoord te vinden en pas als het echt niet lukt, dan mag je bij Oplossing 1a spieken.

▶▶▶ Zoek *Opdracht 1a* in het bestand `index.html` en voeg de code op de juiste plaats toe.

<details>
  <summary>Oplossing 1a</summary>

>  &lt;head&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;&lt;title&gt;Mijnenveger&lt;/title&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;&lt;meta http-equiv="content-type" content="text/html; charset=UTF-8"&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;**&lt;link rel="stylesheet" href="css/mijnenveger.css" type="text/css"&gt;**<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;**&lt;script type="text/javascript" src="js/mijnenveger.js"&gt;\&lt;/script&gt;**<br>
>  &lt;/head&gt;<br>
</details>

#### Opdracht 1b: Hoe heet ik?
Op de pagina willen we graag de naam van het spel `Mijnenveger`als kop in grootte 2 hebben. Onder de kopregel moet een horizontale scheidslijn komen. Voeg de benodigde code hiervoor toe in het bestand `index.html`.

▶▶▶ Zoek *Opdracht 1b* in het bestand `index.html`en voeg de benodigde code op de juiste plaats toe.

<details>
  <summary>Oplossing 1b</summary>
	 **&lt;h2&gt;Mijnenveger&lt;/h2&gt;&lt;hr&gt;**	
</details>

![](images/1.png) `hier een afbeelding van pagina met elementen erin`


### Opdracht 2: Spelinstructies

Als we Mijnenveger gaan spelen, dan moeten we wel weten wat de bedoeling is van het spel en hoe de speler het spel moet spelen. Je gaat zorgen dat er een pop-up venster met spelinstructies verschijnt als op de __HELP__ knop wordt geklikt.

Laten we de __HELP__ knop op het scherm tekenen.

▶▶▶ Zoek *Opdracht 2* in het bestand `.....`<br>
Voeg op de juiste plek in de code de spelinstructies en de HELP knop toe.







# Vanaf hier moet nog verder worden uitgewerkt #
▶▶▶ Vul voor het linker batje `2 * roosterGrootte` in in de functie `maakBatje`.

Het rechter batje moet getekend worden op 3 keer de grootte van het rooster van de rechterkant van het speelveld. De rechterkant van het speelveld is `speelveld.breedte`. Houdt rekening met de dikte van het batje.

▶▶▶ Vul voor het rechter batje `speelveld.breedte - 3 * roosterGrootte` in in de functie `maakBatje`.

▶▶▶ Kan je bedenken waarom aan de linkerkant 2 keer de roostergrootte wordt opgeteld, en aan de rechterkant 3 keer de roostergrootte wordt afgetrokken?

![](images/2.png)

### Opdracht 3: Het mijnenveld

Tot nu toe gebeurt er nog niet zoveel. Mijnenveger is wel erg saai als er niets beweegt.


▶▶▶ Zoek *Opdracht 3* in het bestand `mijnenveger.js`.

▶▶▶ Tussen de twee markeringen van `Opdracht 3`, vul `tekenVierkant('white', balletje);` in. Vergeet de `;` aan het einde niet.

De functie `tekenVierkant` tekent een vierkant op op het scherm. De functie roepen we aan met twee argumenten: `'white'` (wit in het Engels), de kleur van het balletje en `balletje`, wat bepaalt waar en hoe groot de bal wordt getekend op het scherm.

Nu moet er een balletje verschijnen op het scherm.

![](images/3.png)

### Opdracht 4: Grootte mijnenveld, aantal bommen

De bal moet niet alleen bewegen, maar ook stuiteren! Nu schuift de bal langs de rand van het speelveld. Dat klopt niet!

▶▶▶ Zoek *Opdracht 4* in het bestand `pong.js`. Er staan twee opdrachten, *a* en *b*.

We kunnen de bal laten stuiteren door hem om te laten keren van ritchting als de bal de muur raakt. De bal heeft een functie `keerOm()` om de bal te laten omkeren.

▶▶▶ Zoek *Opdracht 4 (a)*. Hier raakt de bal de bovenste muur. Laat de bal omkeren door `balletje.keerOm();` aan te roepen.

▶▶▶ Zoek *Opdracht 4 (b)*. Hier raakt de bal de onderste muur. Laat de bal omkeren.

Nu moet de bal stuiteren als de bal de bovenste of onderste muur raakt.

![](images/4.png)

### Opdracht 5: Toetsenbord

De batjes staan nu stil aan de linker- en rechterkant van het speelveld. De spelers moeten met toetsen op het toetsenbord de batjes kunnen bewegen.

In de code moeten we *luisteren* naar te toetsen van het toetsenbord. Als een speler een toets indrukt, dan kunnen wij een actie uitvoeren in de code, zoals het bewegen van het batje.

Voor het rechterbatje gebruiken we de pijltjestoetsen omhoog en omlaag. Voor het linkerbatje gebruiken we de toetsen `w` en `s`.

▶▶▶ Zoek *Opdracht 5* in het bestand `pong.js`. Er staan zes opdrachten, *a*, *b*, *c*, *d*, *e*, en *f*.

Per toetsaanslag gaan we het batje laten bewegen. Dat kan met de functies
- `rechterBatje.beweegOmhoog();`
- `rechterBatje.beweegOmlaag();`
- `rechterBatje.stop();`
- `linkerBatje.beweegOmhoog();`
- `linkerBatje.beweegOmlaag();`
- `linkerBatje.stop();`

▶▶▶ Zoek *Opdracht 5 (a)*. Hier wordt 🡹 (pijltje omhoog) ingedrukt op het toetsenbord. Roep de goede functie aan om het rechterbatje omhoog te laten bewegen.

▶▶▶ Zoek *Opdracht 5 (b)*. Hier wordt 🡻 (pijltje omlaag) ingedrukt op het toetsenbord. Roep de goede functie aan om het rechterbatje omlaag te laten bewegen.

▶▶▶ Zoek *Opdracht 5 (c)*. Hier wordt de toets `w` ingedrukt op het toetsenbord. Roep de goede functie aan om het linkerbatje te laten bewegen.

▶▶▶ Zoek *Opdracht 5 (d)*. Hier wordt de toets `s` ingedrukt op het toetsenbord. Roep de goede functie aan.

We hebben de toetsen afgehandeld om te batjes te laten bewegen. Probeer maar eens!

Zoals je kan zien, stoppen de batjes nooit meer met bewegen. Het batje moet stoppen met bewegen zodra een toets wordt *losgelaten*.

▶▶▶ Zoek *Opdracht 5 (e)*. Hier wordt een pijltjestoets losgelaten op het toetsenbord. Roep de goede functie aan.

▶▶▶ Zoek *Opdracht 5 (f)*. Hier worden te toetsen `w` of `s` losgelaten op het toetsenbord. Roep de goede functie aan.

Probeer de batjes te bewegen in het spel. Als je de pijtjestoetsen of `w` of `s` indrukt beweegt het batje. Als je te toetsen loslaat, dan stopt het batje met bewegen.

![](images/6.png)

### Opdracht 6: Wijzigen van toetsen

In opdracht 5 hebben we de batjes laten bewegen. De toetsen waren `w` en `s` voor het linkerbatje.

Laten we de toetsen wijzigen waarmee het linkerbatje gaat bewegen, bijvoorbeeld naar `q` en `a`.

▶▶▶ Zoek *Opdracht 6* in het bestand `pong.js`. Er staan drie opdrachten, *a*, *b* en *c*.

▶▶▶ Bij *Opdracht 6 (a)*. Wijzig de toets `w` naar `q` om het linker batje bij het indrukken van de toets `q` omhoog te laten bewegen.

▶▶▶ Bij *Opdracht 6 (b)*. Wijzig de toets `s` naar `a` om het linker batje bij het indrukken van de toets `a` omlaag te laten bewegen.

▶▶▶ Bij *Opdracht 6 (c)*. Wijzig de toets `w` naar `q` en `s` naar `a` om het linker batje te laten stoppen als een van de toetsen `q` of `a` niet meer worden ingedrukt.

![](images/6.png)

### Opdracht 7: Snelheid

De bal heeft een vaste snelheid. We kunnen de snelheid aanpassen zodat de bal langzamer of sneller beweegt.

▶▶▶ Zoek *Opdracht 7* in het bestand `pong.js`.

Hier staat een waarde `3`. We kunnen de waarde aanpassen naar iets anders om de snelheid van de bal te veranderen.

▶▶▶ Verander de snelheid van de bal naar `1`.

▶▶▶ Verander de snelheid van de bal naar `10`.

▶▶▶ Verander de snelheid van de bal naar `30`.

Kan je het spel nog spelen?

▶▶▶ Verander de snelheid van de bal naar `0`. Wat gebeurt er?

### Opdracht 8: Richting van de bal

Als het spel begint, gaat de bal altijd naar rechtsboven. We kunnen de bal ook naar linksboven, linksonder of rechtsonder laten beginnen.

▶▶▶ Zoek *Opdracht 8* in het bestand `pong.js`.

Er staan twee variabelen: `dx` en `dy`. De variabelen bepalen welke kant de bal op beweegt. Standaard begint de bal naar rechts (`dx` is positief) en naar boven (`dy` is negatief, door de `-`).

▶▶▶ Zet een `-` bij de `dx` erbij. Welke kant gaat de bal op?

▶▶▶ Haal de `-` bij de `dy` weg. Welke kant gaat de bal op?

▶▶▶ Haal de `-` bij de `dx` weer weg. Welke kant gaat de bal op?

### Opdracht 9: Kleuren

Ons Pong spel is zwart en wit, met grijs erbij. Dat is een beetje saai. Laten we het spel wat mooier maken door kleurtjes toe te voegen aan de bal, de muren en de batjes.

▶▶▶ Zoek *Opdracht 9* in het bestand `pong.js`. (Let op, dit zijn meerdere regels.)

Hier worden meerdere functies aangeroepen die dingen tekenen in het spel. Je kan elk onderdeel dat wordt getekend een andere kleur geven door de naam van de kleur op te geven.

▶▶▶ Verander de kleur van de bovenste muur naar `'red'` (*red* is rood in het Engels).

Kan je zien dat de muur rood wordt?

▶▶▶ Open in een nieuw tabblad de website https://htmlcolorcodes.com/color-names/.

Op de website staat een lijst van kleuren met namen. Al deze namen kan je gebruiken als kleurtje.

▶▶▶ Verander de kleur van de bovenste muur, de onderste muur, het linker batje, het rechter batje en van de bal.

![](images/9.png)

### Opdracht 10: Ronde bal

De bal is een vierkant blokje. Eigenlijk is dat vreemd want ballen zijn meestal rond. Laten we onze Pong bal ook rond maken.

▶▶▶ Zoek *Opdracht 10* in het bestand `pong.js`.

Hier staat dat `balletje` als een vierkant wordt getekend.

▶▶▶ Verander de functie aanroep `tekenVierkant` naar `tekenCirkel`.

De bal moet nu als een cirkel worden getekend.

![](images/10.png)

### Opdracht 11: Score tonen

Als een van de spelers een punt scoort, dan begint de bal overnieuw in het midden. Maar we zien niet wie er voor staat.

We gaan de score van de spelers tonen in het speelveld.

▶▶▶ Zoek *Opdracht 11* in het bestand `pong.js`.

Er is een functie `tekenTekst(...)`. Die functie kan tekst tekenen in het speelveld. De argumenten zijn als volgt:
1. De kleur van de tekst.
2. De x-cooördinaat van (het midden van) de tekst.
3. De grootte van de tekst.
4. De tekst.

▶▶▶ Roep de functie `tekenTekst` aan om de score van de linker speler te tekenen:`tekenTekst('lightblue', speelveld.breedte / 2 - 4 * roosterGrootte, roosterGrootte * 5, score.links);`.

Je mag de argumenten variëren. Zie je het getal *0* verschijnen in het speelveld?

▶▶▶ Roep de functie `tekenTekst` aan om de score van de rechter speler te tekenen. Bepaal zelf welke argumenten moeten veranderen om de score op de juiste plek te krijgen.

Nu moeten beide spelers een score in het speelveld hebben staan.

![](images/11.png)

### Opdracht 12: Score tellen

We tonen nu de scores van de spelers, maar er staat altijd *0* in beeld. We moeten de score tellen als er een punt wordt gescoort.

▶▶▶ Zoek *Opdracht 12* in het bestand `pong.js`.

Er staat een `if` en een `else if`. Daarbinnen kan de score van elke speler worden opgehoogd.

Je kunt een speler een punt geven door `score.links += 1;` of `score.rechts += 1;` te typen.

▶▶▶ Zet in de `if` en in de `else if` binnen de `{` en `}` de code neer om de punten op te hogen van de spelers, als er wordt gescoort.

▶▶▶ Probeer de speler 10 punten te geven als er wordt gescoret, in plaats van één punt.

Zie je dat de score wordt opgehoogd als een speler een punt scoort? Goed zo!

![](images/12.png)

### En verder

De opdrachten zijn klaar. Maar wie weet heb je in de tussentijd zelf ideeën gekregen om het spel verder uit te breiden. Ga je gang, probeer gerust dingen te veranderen en te verbeteren!



Suggesties voor opdrachten voor de code:
-   kleuren aantal aangrenzende vakken met bom erin van mono kleur veranderen naar eigen kleur per nummer
-   
-   de functie game-over opbouwen als op een bomveld wordt geklikt
-   button toevoegen om een nieuw spel te starten na eindige vorige spel
-   de kleur van geflagde velden naar eigen smaak veranderen
-   de veldgrootte veranderen (css) mits ook de karaktergrootte bom en getal bomvelden daarmee in overeenstemming zijn te brengen.
-   het spel met de boolean alive manipuleren

Extra opdrachten:
-   toevoegen van instel opties in het scherm om aantal kolommen, rijen en bommen in te stellen (nu hardcoded in js).
-   teller die afloopt naar 0 met max tijd welke speler krijgt om na vorige vak een volgend vak te openen.
-   oplopende moeilijkheid inbouwen bij elke keer dat het spel slaagt of via een levelkeuze (van klein veld of weinig bommen naar steeds groter mijnengebied met meer bommen.
-   Verfraaiing door bom afbeelding en andere visuele opmaak op de pagina toe te voegen (bijv in titelgebied)
