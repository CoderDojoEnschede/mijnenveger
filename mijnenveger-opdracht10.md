# Opdracht 10: Speluitleg<hr>

Het kan zijn dat mensen het spel mijnenveger nog nooit gespeeld hebben en niet weten hoe het werkt of wat de bedoeling van het spel  is.

Je gaat op de spelpagina een button `speluitleg` maken die de pagina `speluitleg.html` opent. We hebben al een lege pagina `speluitleg.html` voor je voorbereid, maar deze moet nog gevuld worden. Vul de pagina met tekst die het spel uitlegt. Je kan hiervoor gebruik maken van de tekst die op de startpagina staat, maar je mag ook je eigen tekst verzinnen. Ook op [Wikipedia](https://nl.wikipedia.org/wiki/Mijnenveger_(spel)) vind je teksten die je kunt gebruiken. Onderin de pagina maak je een button die de speluitleg pagina weer sluit als erop geklikt wordt.

▶▶▶ Open het bestand `index.html`. Voeg een button voor het openen van `speluitleg.html` toe. In het voorbeeld hebben we de button direct boven &lt;/body&gt; gezet, maar je mag ook een andere plek op je pagina kiezen waar de button moet komen.

<details>
<summary>Button `speluitleg.html` openen</summary>
Onderstaande button opent de speluitleg pagina in een nieuw venster.
>&lt;form action="speluitleg.html" method="get" target="_blank"&gt;  
&emsp;&lt;button type="submit"&gt;Speluitleg&lt;/button&gt;  
&lt;/form&gt;  
</details>
<br>


▶▶▶ Open het bestand `speluitleg.html`. Zorg voor een passende titel voor het browservenster in deze pagina. In de body zet je een &lt;h1&gt; koptekst en daaronder plaats je uitleg over wat de bedoeling van het spel is. Helemaal onderaan de pagina maak je een button waarmee de pagina kan worden gesloten. Probeer eerst zelf het antwoord te vinden hoe je dit moet doen. Als dat niet lukt mag je bij de oplossingen hieronder kijken.

<details>
<summary>Titel</summary>
Zoek de regel met &lt;title&gt; &lt;/title&gt; en geef de pagina een goede titel.
>&lt;title&gt;Mijnenveger speluitleg&lt;/title&gt;
</details>

<details>
<summary>Koptekst</summary>
De koptekst moet in de body (tussen &lt;body&gt; en &lt;/body&gt;) komen.
>&lt;h1&gt;Mijnenveger speluitleg&lt;/h1&gt;
</details>

<details>
<summary>Button pagina sluiten</summary>
Onderstaande button sluit de pagina.
>&lt;input type="button" value="Sluit deze pagina" onclick="self.close()"&gt;  
</details>

Na het maken van deze en alle voorgaande opdrachten is je spel af en kun je het gaan spelen. Wil je nog graag verder programmeren aan dit spel en het nog beter maken, kijk dan eens bij de bonus opdrachten voor ideeën.

<hr>
<center>
&emsp;<a href="./mijnenveger-opdracht9.md">Opdracht 9</a>
&emsp;<a href="./Instructies.md">Start</a> 
&emsp;<a href="./mijnenveger-bonus.md">Bonus opdrachten</a>
</center>


