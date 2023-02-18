# Opdracht 10: Speluitleg pagina<hr>

Het kan zijn dat mensen het spel mijnenveger nog nooit gespeeld hebben en niet weten hoe het werkt en wat de bedoeling is.

Je gaat zelf op de spelpagina een button `speluitleg` maken die de pagina `speluitleg.html` opent. We hebben al een lege pagina `speluitleg.html` voor je voorbereid, maar deze is nog leeg. Vul de pagina met tekst die het spel uitlegt. Je kan hiervoor gebruik maken van de tekst die op de startpagina staat, maar je mag ook je eigen tekst verzinnen. Onderaan de pagina maak je een button die de speluitleg pagina weer sluit.

▶▶▶ Open het bestand `index.html`. Voeg een button voor het openen van `speluitleg.html` toe. In het voorbeeld hebben we de tekst direct boven &lt;/body&gt; gezet, maar je mag ook een andere plek op je pagina kiezen waar de button moet komen.

<details>
<summary>Button `speluitleg.html` openen</summary>
Onderstaande button opent de speluitleg pagina in een nieuw venster.
>&lt;form action="speluitleg.html" method="get" target="_blank"&gt;  
&emsp;&lt;button type="submit"&gt;Speluitleg&lt;/button&gt;  
&lt;/form&gt;  
</details>
<br>


▶▶▶ Open het bestand `speluitleg.html`. Zorg voor een passende titel voor deze pagina. In de body zet je een &lt;h1&gt; koptekst en daaronder plaats je uitleg over wat de bedoeling van het spel is. Onderaan de pagina maak je een button, zodat na het lezen de pagina daarmee kan worden gesloten. Probeer eerst zelf het antwoord te vinden hoe je dit moet doen. Als dat niet lukt mag je bij de oplossingen hieronder kijken.

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

Na het maken van alle voorgaande opdrachten, is je spel af en kun je het gaan spelen. Wil je nog graag verder programmeren aan dit spel en het nog beter maken, kijk dan eens bij de bonus opdrachten. Maar je mag ook je eigen fantasie volgen.

<hr>
<center>
&emsp;<a href="./mijnenveger-opdracht9.md">Opdracht 9</a>
&emsp;<a href="./Instructies.md">Start</a> 
&emsp;<a href="./mijnenveger-bonus.md">Bonus opdrachten</a>
</center>


