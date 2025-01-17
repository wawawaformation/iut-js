# Les tâches à réaliser

- On fait apparaitre et disparaitre le menu au click sur l'icone burger
    1. on identifie les éléments #burger et .menu-principal
    2. on ajoute un gestionnaire d'évènement à l'icone burger (type click)
    3. on ajoute ou modifie la classe .hideme
    4. on modifie un peu le css pour en dessous de 681px, la classe hideme fait disparaitre le menu
- On calcule l'imc et on donne la réponse en sélectionnant le bon objet dans le json founi
    1. on identifie le formulaire
    2. on y ajoute un gestionnaire d'évènement
    3. on oublie pas le preventDefault
    4. on calcul l'imc 
    5. on va cherche l'objet correspondant
    6. on cree un noeud reponseElt qu'on ajoute à main
    7. on ajoute l'imc, le titre, texte et la couleur
    8. amelioration :
        - on affiche une erreur si la taille ou le poids sont invalides
        - On utilise des animations
- On raccourci les liens à partir de 900px jusqu'à 681px 