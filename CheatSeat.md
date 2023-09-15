# JavaScript Cheat Sheet


VARIABLES :
-----------
Déclaration : let nomVariable;
Assignation : nomVariable = valeur;
Constante : const nomConstante = valeur;

TYPES DE DONNÉES :
------------------
Nombre : let nombre = 42;
Chaîne de caractères : let texte = "Hello, World!";
Booléen : let estVrai = true;
Tableau : let tableau = [1, 2, 3];
Objet : let objet = { clé1: "valeur1", clé2: "valeur2" };

OPÉRATEURS ARITHMÉTIQUES :
--------------------------
Addition : +
Soustraction : -
Multiplication : *
Division : /
Modulo (reste de la division) : %

OPÉRATEURS DE COMPARAISON :
---------------------------
Égalité : ==
Égalité stricte : ===
Différence : !=
Inférieur : <
Supérieur : >
Inférieur ou égal : <=
Supérieur ou égal : >=

STRUCTURES DE CONTRÔLE :
------------------------
Condition If-Else :
if (condition) {
    // Instructions si vrai
} else {
    // Instructions si faux
}

Boucle While :
while (condition) {
    // Instructions répétées
}

Boucle For :
for (let i = 0; i < limite; i++) {
    // Instructions répétées
}

Fonctions :
function nomFonction(paramètre1, paramètre2) {
    // Instructions
    return résultat;
}

Appel de fonction :
let résultat = nomFonction(arg1, arg2);

TABLEAUX ET OBJETS :
---------------------
Accéder à un élément de tableau : tableau[indice]
Ajouter un élément à un tableau : tableau.push(valeur)
Accéder à une propriété d'un objet : objet.clé
Modifier une propriété d'un objet : objet.clé = nouvelleValeur

ITERATION SUR UN TABLEAU :
--------------------------
tableau.forEach(function (élément) {
    // Instructions pour chaque élément
});

MAP :
const nouveauTableau = tableau.map(function (élément) {
    // Transformation de chaque élément
    return nouveauÉlément;
});

FILTRE :
const tableauFiltré = tableau.filter(function (élément) {
    // Condition de filtrage
    return condition;
});