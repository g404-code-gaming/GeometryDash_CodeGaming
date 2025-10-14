# Animation et visuel 

### Ajout de particules ✨:

Pour rendre le jeu plus visuellement intéressant, nous pouvons ajouter des particules qui sont émises lorsque le personnage court et saute. Ces particules peuvent ressembler à de la poussière, des étincelles, etc.

Les particules proviennent d'un objet spécial appelé **émetteur de particule** (*particle emitter* en anglais)

Crée un émetteur de particule puis placer le à l'arrière de notre personnage au sol.
À chaque instant, on va modifier la position pour chaque déplacement du joueur.

![ParticuleDeplacement](Images/ParticuleDeplacement.png)

Suite à cela, on voudrait que l'émission se réalise seulement quand le personnage est au sol. On réalisera alors un arrêt d'émission de particules lorsque le player ne sera plus détecter comme au sol.

![EmissionSaut](Images/EmissionSaut.png)

### Animation de saut 🏃‍♂️:

Lorsque le personnage saute, une animation de saut est jouée. Ces animations donnent l'impression que le personnage saute et surtout évite de rester immobile.
Lorsque le personnage ne sera pas en contact avec le sol, on ajoutera une rotation au player.

![RotationJump](Images/RotationJump.png)

À la fin de cette partie, vous devriez en être ici au niveau du code.

![EndPartJumpCode](Images/EndPartJumpCode.png)

# 🏁 Fin du parcours

La fin du parcours est un élément crucial de tout niveau de Geometry Dash. C'est l'objectif que le joueur essaie d'atteindre, et c'est ce qui marque la fin du défi.

## Placement de la porte 🚪

La fin du parcours est généralement marquée par une porte ou un autre [objet](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Objets.md) de fin de niveau. Cette porte doit être placée à un endroit qui ne peut être atteint que si le joueur a réussi à naviguer à travers tous les obstacles du niveau.

## Code de fin de niveau 💻

Lorsque le personnage atteint la porte, nous devons exécuter un certain [code](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/%C3%A9v%C3%A8nements.md) pour marquer la fin du niveau. Cela pourrait inclure l'arrêt du mouvement du personnage, la lecture d'une animation de fin de niveau, l'affichage d'un écran de victoire, etc.

![EndCode](Images/EndCode.png)

(le code est impressionnant, mais il est surtout composé de ligne dédiée a l'animation si vous ne voulez pas d'animation, vous avez juste à réaliser la dernière ligne de code)

Félicitations ! 🎉 Tu as réussi à créer ton propre Geometry Dash ! 🎮 C'est une réalisation impressionnante. Tu as pris un concept de jeu populaire et tu l'as fait tien, en utilisant tes compétences en codage et en design. 

Maintenant, c'est à toi de jouer ! 🕹️ Tu as les bases, mais il y a encore tant de possibilités. Pourquoi ne pas ajouter de nouvelles mécaniques de jeu ? Des power-ups, des ennemis, des niveaux secrets... Laisse libre cours à ta créativité et fais de ce Geometry Dash quelque chose d'unique.

Tu devrais être fier de ce que tu as accompli. Continue à explorer, à apprendre et à créer. Qui sait quel jeu incroyable tu vas créer ensuite ? Bravo à toi ! 👏
