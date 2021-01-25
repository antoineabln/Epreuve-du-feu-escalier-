# Epreuve-du-feu-escalier-

const char = prompt("entrez un caractère ou une chaine de caractère");

let controleur = prompt("entrez le nombre de répétition");

let controleur2 = controleur;

let espace = " "

for (let i = 1; i <= controleur ; i++){
  
 console.log(`${espace.repeat(controleur2--)}` + `${char.repeat(i)}`);
  
}
