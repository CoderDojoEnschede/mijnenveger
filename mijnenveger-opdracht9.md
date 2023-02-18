# Opdracht 9: Spelen met de grootte van de vakjes<hr>

Het kan zijn dat je na het aanpassen van de aantallen bij rijen en kolommen net te weinig beeldscherm hebt om niet te hoeven scrollen. Hoewel het voor het uiterlijk niet aan te bevelen is om de vakjes te klein te maken, is het wel mogelijk om iets te spelen met de grootte van de karakters. Hierdoor kun je de ruimte op het scherm van het mijnenveld wat groter of kleiner maken en daardoor voorkomen dat scrollen nodig is. Maak je de vakjes te klein, dan passen mogelijk de cijfers en bommen niet meer netjes in de vakjes.

▶▶▶ Zoek *Opdracht 9a en 9b* op in het bestand `mijnenveger.js` en experimenteer met de grootte van de vakjes (9a) en de font size (9b), maar zorg er wel voor dat de cijfers en de bom nog netjes passen binnen de vakjes.

<details>
<summary>Oplossing 9a</summary>
Pas `width, min-width, height, min-height` aan naar zoals jij de grootte van de vakjes in schermpixels mooi vindt.  
>#veld table td {  
&emsp;background-color: rgb(195, 195, 195);  
<b>&emsp;width: 30px;  
&emsp;min-width: 30px;  
&emsp;height: 30px;  
&emsp;min-height: 30px;</b>  
&emsp;border: 1px solid black;  
}  
</details>


<details>
<summary>Oplossing 9b</summary>
Je mag voor de `font-size` een passen waarde kiezen voor jouw mijnenveld size.  
>#veld table {  
&emsp;border-collapse: collapse;  
<b>&emsp;font-size: 150%;</b>  
&emsp;font-family: san-serif;  
&emsp;font-weight: bold;  
&emsp;display: inline-block;  
}  
</details>


Als je tevreden bent, ga dan verder met de laatste opdracht 10.

<hr>
<center>
&emsp;<a href="./mijnenveger-opdracht8.md">Opdracht 8</a>
&emsp;<a href="./Instructies.md">Start</a> 
&emsp;<a href="./mijnenveger-opdracht10.md">Opdracht 10</a>
</center>


