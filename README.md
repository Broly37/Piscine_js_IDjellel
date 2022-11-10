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

ex3
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
