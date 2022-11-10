# Piscine_js_IDjellel
/* Ecrivez une fonction substract qui prend deux paramètres et qui retourne la soustraction des deux paramètres. Votre fonction devra se nommer substract */

function substract(nb1,nb2){
return nb1 - nb2;
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  substract
}

ex2
/* Ecrivez une fonction qui prend deux paramètres et qui retourne la somme des deux paramètres. Votre fonction devra se nommer add */

function add(nb1,nb2){
return nb1 + nb2;
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  add
}

/* Ecrivez une fonction multiply qui prend deux paramètres et retourne la multiplication des deux paramètres */


function multiply (nb1,nb2) {
return nb1 * nb2; 
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  multiply
}

ex4
/* Ecrivez une fonction divide qui prend en paramètre deux arguments et qui retourne la division du premier par le second, attention la division par zéro est interdite et doit retourner la chaîne de caractère Forbidden */

function divide (nb1, nb2){
if (nb2 == 0) {
  return("Forbidden")
} else {
  return nb1/nb2;
  }
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  divide
}

5
/* Ecrivez une fonction modulo qui prend deux paramètres en arguments et qui retourne le premier paramètre modulo le deuxième paramètre */

function modulo (nb1, nb2){
return nb1%nb2
  }

// Ne touchez pas les lignes en dessous.
module.exports = {
  modulo
}

6
/* Ecrivez un programme qui affiche uniquement les nombres de 0 à 10 à l'aide d'une variable i */

//Testez votre programme sur index.js
for(let i = 0; i<= 10;i++){
 console.log(i);
}


/* la console doit afficher  :
0
1
2
3
4
5
6
7
8
9
10
*/

7 
/* Créez un programme qui affiche uniquement les nombres pairs de 2 à 100, à l'aide d'une variable */

// Testez votre programme sur index.js


for(let i = 2; i<=100; i= i+2) {
 console.log(i);
}
console.log("fin du programme")


/* la console doit afficher  :

2
4
6
8
10
...
98
100
*/

8
// Hello user ! 
/* Ecrire un programme qui affiche dans la console le texte suivant (OUTPUT).
Le programme doit demander à l'utilisateur son prénom. Et ensuite lui souhaiter une belle journée avec son prénom indiqué.

===== OUTPUT =====

Hello user !
How are you today ? What is your name ?> Peter
Have a nice day Peter !

===============

Explications du programme, Peter est le nom indiqué par l'utilisateur, le programme sera testé avec différentes valeurs et devra affiché la valeur indiqué par l'utlisateur lors de la demande du programme.
*/


// Pensez à tester votre programme sur index.js

console.log("hello user!")
let name= prompt("how are you today ? what's your name ?")
console.log("Have a nice day " +name + ' !')

9

//Pensez à tester votre code sur index.js

  */
console.log("Welcome to my secret diary !")
const name = prompt("What's your name ?")
if (name==="David"){
  console.log("I really wanna stay at your house, and i hope this works out");
}else{
  console.log("Get away!");
}
