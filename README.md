# Description des fichiers .RPGLE / .SQLRPGLE


## POKEMAIN.RPGLE
Gère le menu principal. Programme appelé pour lancer le jeu.

<ins>Écrans (.DSPF) utilisés :</ins>
- EPOKEMAIN

<ins>Programmes externes appelés :</ins>
- POKEJEU.SQLRPGLE
- POKEDEX.SQLRPGLE


## POKEJEU.SQLRPGLE
Lance le jeu.

<ins>Programmes externes appelés :</ins>
- POKEDIAL.SQLRPGLE

<ins>Écrans (.DSPF) utilisés :</ins>
- EPOKEJEU


## POKEDEX.SQLRPGLE
Affiche le Pokédex complet.

<ins>Écrans (.DSPF) utilisés :</ins>
- EPOKEDEX


## POKEDIAL.SQLRPGLE
Gère les boîtes de dialogue (WINDOW).

<ins>Paramètres d'entrée :</ins>
- id_dialogue INT(10)

<ins>Écrans (.DSPF) utilisés :</ins>
- EPOKEMAIN

