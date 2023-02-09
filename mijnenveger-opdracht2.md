# Opdracht 2: Het mijnenveld zichtbaar maken<hr>

Klik maar eens wat rond op het speelscherm. Je zult zien dat er wel wat gebeurt als je op sommige plekken in het browservenster klikt. Maar hoe weet je waar je precies moet klikken? Geen idee, dat kunnen we nu niet zien.

Het mijnenveld en de afzondelijke vakjes, worden gemaakt door een tabel. Om die zichtbaar te maken, gaan we de afzonderlijke tabel cellen voorzien van een rand.

De tabelopmaak code (CSS) staat in het bestand `mijnenveger.css`<br>

▶▶▶ Zoek *Opdracht 2* op in het bestand `mijnenveger.css` en verander de code dusdanig dat de vakjes een zichtbare rand van 1 pixel breed krijgen, zodat het scherm er uit ziet als in de afbeelding.

<img src="images/mijnenveger1_1.png" alt="drawing" width="600"/><br>
  
Probeer eerst zelf het antwoord te vinden voor je het opzoekt of controleert.

<details>
  <summary>Oplossing 2</summary>
>  #veld table td {<br>
    &emsp;background-color: rgb(195, 195, 195);<br>
    &emsp;width: 30px;<br>
    &emsp;min-width: 30px;<br>
    &emsp;height: 30px;<br>
    &emsp;min-height: 30px;<br>
    &emsp;**border: 1px solid black;**<br>
}<br>
</details>

Herstart nu het spel door toets F5 te drukken. Beter zo?

<hr>
<center>
&emsp;<a href="./mijnenveger-opdracht1.md">Opdracht 1</a>
&emsp;<a href="./Instructies.md">Start</a> 
&emsp;<a href="./mijnenveger-opdracht3.md">Opdracht 3</a>
</center>


