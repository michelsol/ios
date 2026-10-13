# IOS

[IOS](https://michelsol.github.io/ios/ios.html) est une interface pour corriger les copies par ordinateur.

L'interface est [open-source](https://github.com/michelsol/ios) sous [licence GNU GPL](https://github.com/michelsol/ios/blob/main/LICENSE) et fonctionne strictement sans serveur, sur votre ordinateur.

Vous pouvez télécharger la page de l'interface et couper internet lors de l'utilisation si vous le souhaitez.

## Exemples clé en main

L'interface s'ouvre avec un lot de copies déjà chargé, prêt à corriger. Rien à installer ni à télécharger.

[Premier exemple (Gros contrôle)](https://michelsol.github.io/ios/examples/example_2.html).
[Enoncé et corrigé](https://michelsol.github.io/ios/examples/correction_2.pdf).

[Deuxième exemple (Petit contrôle)](https://michelsol.github.io/ios/examples/example_1.html).
[Enoncé et corrigé](https://michelsol.github.io/ios/examples/correction_1.pdf).

### Avantages

* Confort mental : Possible de corriger transversalement avec très peu d'informations en tête.
* Confort physique : Mouvements de faible amplitude, position relâchée.
* Gain de temps ou de qualité de correction possible pour les grands contrôles
* Informatisation de toutes les copies => triche ultérieure impossible, post-traitement informatisé des copies possible.

### Inconvénients 

* Temps de préparation et de finalisation non négligeables => peu rentable pour petits contrôles.
* Commentaires non précisément localisés (Cependant, il existe un bouton pour annoter au stylo rouge, des captures d'écran rectangulaires)
* Usage de papier, d'encre, d'agrafes, pour imprimer les notes et commentaires (possibilité de condenser le format d'export)

## Comment l'utiliser ?

### Préparation (\~ 10 min)

1. Scanner un lot de copies comme un seul fichier PDF consolidé.
2. [Ouvrir l'interface](https://michelsol.github.io/ios/ios.html), puis cliquer sur le dossier en haut à gauche pour charger le PDF scanné.
3. Créer la liste des questions et les points possibles associés à chaque question (grand + bleu à droite)

   * Pour chaque question, on doit spécifier le titre, les points possibles, et éventuellement un titre d'exercice
   * Les points possibles ont par ex. le format 0 1 \| 0.25 0.5 0.75. Les points fréquents avant \| sont affichés horizontalement, les points peu fréquents après \| sont suggérés en liste déroulante verticale.
   * Pour les gros contrôles, spécifier les exercices permet d'expliciter des sous-totaux.
   * Pour les petits contrôles, il est préférable de ne pas spécifier de titre d'exercice, pour gagner de la place sur le format exporté.
4. Créer la liste des étudiants à droite, avec le + en bas de la liste déroulante des étudiants.

   * Vous pouvez copier une liste de noms d'élèves depuis un tableur (téléchargée par ex. depuis pronote), et la coller directement (CTRL+v) dans le nom d'un nouvel étudiant.
   * Un nouvel étudiant reçoit la page du PDF affichée, et le groupe de l'étudiant précédent.
5. Faire un premier passage sur le lot. A chaque passage sur une nouvelle copie :

   * Sélectionner l'étudiant correspondant
   * Appuyer sur la feuille avec un point rouge, pour associer la page du PDF, à cet étudiant.
   * Le crayon à droite de l'étudiant permet de modifier son nom, sa page et son groupe (par ex. sujet A ou B). Pendant la modification, la feuille avec un point rouge reporte la page affichée.
   * En cas de mauvais ordre ou orientation, il est possible de modifier le PDF en haut à gauche.
6. Il est possible de trier la liste des étudiants aléatoirement, puis par groupe (pour mettre les sujets A avant les sujets B), dans la toolbar de la liste des étudiants.
7. Enregistrer (Ctrl + S) en cliquant sur le bouton de sauvegarde sur la partie droite.
Les sauvegardes sont des fichiers ODS manuellement lisibles, et modifiables avec un tableur.

### Notation

8. Noter les copies en faisant des sauvegardes régulières (Ctrl + S). Il est préférable de désactiver l'ouverture automatique des fichiers téléchargés.

   * La correction peut se faire de façon transversale en traitant toutes les copies successivement, pour chaque question ou petit groupe de questions dépendantes.
   * En cas de correction transversale, penser à enclencher la feuille avec un point rouge, pour garder en mémoire la position précise du défilement dans le PDF pour chaque étudiant.
   * Si vous corrigez à la souris, vous pouvez sauter à l'étudiant suivant avec le clic molette, ce qui permet de corriger des questions simples en bougeant très peu la main.
   * Les commentaires déjà écrits (découpés au « ; ») sont proposés automatiquement dans la liste déroulante, les plus utilisés en premier. Taper les premières lettres filtre la liste, et la première suggestion s'écrit en bleu à la suite : continuer à taper la remplace, Entrée l'accepte (une seconde fois Entrée valide le commentaire). Un clic dans la case déroule ou replie la liste. De même pour les appréciations.
   * Pour éviter d'alterner fréquemment entre clavier et souris, vous pouvez aussi corriger exclusivement au clavier. (Voir raccourcis plus bas). Les raccourcis types VIM (h/j/k/l au lieu des flèches) permettent de garder les mains centrées sur le clavier et de réduire les mouvements.

### Finalisation (\~ 10 min)

9. Trier les étudiants par page (dans la toolbar de la liste des étudiants), pour les remettre dans le même ordre que le lot initialement scanné.
10. Appuyer sur l'icone d'impression en haut à droite pour exporter dans un format imprimable.
11. Imprimer. Attention à retirer les entêtes éventuelles, préférer des marges étroites.
12. Découper les résultats
* Il faut être très vigilant à cette étape, on peut facilement mélanger les papiers et perdre l'ordre des copies.
* Vérifier que vous avez bien fait l'étape 9, sinon il faut refaire 9,10,11
* Découper d'abord dans le sens de la longueur (3 colonnes par défaut), puis en largeur
* Il existe des coupes papiers très pratiques avec une lame coulissante, trouvable en ligne pour une dizaine d'euros.
* On peut découper chaque colonne de haut en bas, de gauche à droite, puis placer les papiers dans une pile à l'envers, pour obtenir le même ordre que les copies.
13. Agrafer les résultats sur les copies.
* Pour accélérer cette phase, une petite agrafeuse qui tient dans la main est préférable, pour éviter de la reposer à chaque fois.
* Pour des petits contrôles sur feuille recto/verso, une fois les élèves habitués, il peut être envisageable de ne pas agrafer et de rendre les papiers en même temps que les copies.
14. Trier les étudiants par ordre alphabétique (dans la toolbar de la liste des étudiants), sauvegarder, ouvrir le ODS à la feuille "Total", puis copier coller dans Pronote ou autre logiciel. (Plus rapide à faire qu'à la main)

## Raccourcis clavier

La zone de notation peut se parcourir entièrement au clavier.

|Touche|Effet|
|-|-|
|↑ / k|question précédente|
|↓ / j|question suivante|
|← / h|étudiant précédent|
|→ / l / Clic molette|étudiant suivant|
|0-9|mettre la première note du barème qui contient ce chiffre|
|Retour arrière / Suppr|effacer la note de la question|
|Espace|éditer le commentaire de la question courante|
|Maj + Espace|spécifier une note manuellement|
|Maj + ↑ / ↓ · Maj + k / j|faire défiler le PDF|
|Page préc. / suiv.|page précédente / suivante du PDF|
|Ctrl + S|enregistrer les notes au format ODS|
|↑ / ↓ · Tab / Maj + Tab|dans une liste : dérouler les suggestions|

## Astuces

* Pour recharger un travail précédent, importer la dernière sauvegarde (dossier en haut à droite), et rouvrir le PDF associé (dossier en haut à gauche).
* Pour une appréciation commune à une tranche de notes (par ex. « Excellent travail ! » à partir de 16/20), cliquer sur les bulles au bout de la barre d'appréciation.
