# timers
# A quoi sert?

Compteur du temps écoulée dans exécution d'un projet la première fonction "timespent" est un compteur basé sur l'horodatage qui permet d'enregistrer le temps écoulé entre l'ouverture du serveur et sa fermeture ensuite il enregistre le temps dans un fichier  .
  "timer" est un compteur classique qui démarre lors d'ouvertures du serveur et affiche dans le terminal le temps en fonction des secondes.

# Installation 

npm i timers

# usage
> require 

const timers = require('timers');


# API 

> constructeur

const timers = new timers();

> start 

timers.timeSpent(); // pour enregister dans un fichier

timers.timer(); // affichage dans la console
