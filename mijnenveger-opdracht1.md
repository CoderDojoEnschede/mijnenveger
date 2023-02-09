# Opdracht 1: De eerste schreden<hr>

Op de webpagina gebeurt nog niet zoveel. Dat komt omdat de benodigde opmaakcode en JavaScript code nog niet worden gebruikt in je spel. De reden is dat deze code niet in index.html` hebben gezet, maar dat de benodigde code in aparte bestanden staat waar ons spel nog niet bij kan. Dat gaan we veranderen.

Om de code in de aparte bestanden toe te voegen (include), moeten we een verwijzing opnemen naar die bestanden. De verwijzingen moeten in de *&lt;head&gt;* sectie komen in het bestand `index.html`.


## Opdracht 1a: Pagina opmaak

De opmaak code (CSS) staat in het bestand `mijnenveger.css`<br>

Zoek zelf uit welke instructie nodig is om dit bestand met css code op te nemen in het spel.

Probeer eerst zelf het antwoord te vinden en pas als het echt niet lukt, dan mag je bij Oplossing 1a spieken.

▶▶▶ Zoek *Opdracht 1	a* in het bestand `index.html` en voeg de code op de juiste plaats toe. _Hint: je hebt de tag &lt;link&gt; voor het opmaak (css) bestand_

<details>
  <summary>Oplossing 1a</summary>

>  &lt;head&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;&lt;title&gt;Mijnenveger&lt;/title&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;&lt;meta http-equiv="content-type" content="text/html; charset=UTF-8"&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;**&lt;link rel="stylesheet" href="css/mijnenveger.css" type="text/css"&gt;**<br>
>  &lt;/head&gt;<br>
</details>

Merk op wat het effect van het toevoegen van de opmaak code is voor je webpagina (rechterdeel van het browser scherm).

## Opdracht 1b: Spel logica

Het spel heeft JavaScript nodig om goed te kunnen werken. Om de benodigde code beschikbaar te maken moeten we, net als bij de opmaak, een verwijzing opnemen in de head sectie in `index.html` naar het bestand met de JavaScript code.

De benodigde JavaScript code halen we uit het bestand `mijnenveger.js`

Probeer eerst zelf het antwoord te vinden voordat je het antwoord controleert bij oplossing 1b spieken.

▶▶▶ Zoek *Opdracht 1b* in het bestand `index.html` en voeg de code op de juiste plaats toe. _Hint: je hebt de tag &lt;script&gt; nodig voor het JavaScript bestand_


<details>
  <summary>Oplossing 1b</summary>

>  &lt;head&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;&lt;title&gt;Mijnenveger&lt;/title&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;&lt;meta http-equiv="content-type" content="text/html; charset=UTF-8"&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;&lt;link rel="stylesheet" href="css/mijnenveger.css" type="text/css"&gt;<br>
>  &nbsp;&nbsp;&nbsp;&nbsp;**&lt;script type="text/javascript" src="js/mijnenveger.js"&gt;&lt;/script&gt;**<br>
>  &lt;/head&gt;<br>
</details>

## Opdracht 1c: My name is ...
Op de pagina willen we graag de naam van het spel `Mijnenveger`als kop in grootte 2 hebben. Onder de kopregel moet een horizontale lijn komen. Voeg de benodigde code hiervoor toe in het bestand `index.html`.

▶▶▶ Zoek *Opdracht 1c* in het bestand `index.html` en voeg de benodigde code op de juiste plaats toe.

<details>
  <summary>Oplossing 1c</summary>
	 <b>&lt;h2&gt;Mijnenveger&lt;/h2&gt;&lt;hr&gt;</b>	
	 <br>Deze code moet in de body van index.html komen.
</details>

Het resultaat moet eruit zien als in de afbeelding hieronder<br><br>
<center>
<img src=images/mijnenveger1_1.png width=50%/><br>

&emsp;<a href="./mijnenveger-opdracht0.md"><-- De werkomgeving</a>
&emsp;<a href="./Instructies.md">Start</a> 
&emsp;<a href="./mijnenveger-opdracht2.md">Opdracht 2 --></a>
</center>


