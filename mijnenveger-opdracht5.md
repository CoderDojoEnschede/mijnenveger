# Opdracht 5: Game Over...<hr>

Op dit moment kun je nog onbeperkt doorklikken in het spel, ook als de bom verschijnt of alle vakjes gevuld zijn. Dat hoort natuurlijk niet. We willen dat het spel stopt als je een vakje met een bom hebt geopend en dat er een melding verschijnt dat je op een bom bent gestapt.

Om dat voor elkaar te krijgen is de functie gameOver toegevoegd, maar nog niet actief. Haal de commentaartekens weg voor de opdrachten, zodat deze functie ook meedoet in het spel.

▶▶▶ Zoek *Opdracht 5* op in het bestand `mijnenveger.js` en verwijder de commentaartekens voor de regels van de functie gameOver. Let op dat je de commentaartekens niet weghaalt voor de teksten die markeren waar opdracht 5 staat.

<details>
  <summary>Oplossing 5</summary>
>// ▼▼▼ Opdracht 5 ▼▼▼ //  
function gameOver() {  
&emsp;components.alive = false;  
&emsp;document.getElementById('game-over').style.display="block";  
}  
// ▲▲▲ Opdracht 5 ▲▲▲ //</details>

Herstart nu het spel door op F5 te drukken en zoek maar snel een vakje met een bom op. Het spel moet nu netjes eindigen. 

Ga nu verder met opdracht 6.

<hr>
<center>
&emsp;<a href="./mijnenveger-opdracht4.md">Opdracht 4</a>
&emsp;<a href="./Instructies.md">Start</a> 
&emsp;<a href="./mijnenveger-opdracht6.md">Opdracht 6</a>
</center>


