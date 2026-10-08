l’identifiant court du premier commit : 55e8de1

le commit correspondant à l’ajout de la page Contact : 2963a69

le nombre actuel de commits : 7 commit

la commande utilisée pour afficher l’historique sous forme graphique : git log --oneline --graph --all 

commande utilisée : git show 2963a69

cette méthode est différente car elle permet de faire un retour en arrière directement sur le commit précédent en retirant les modifications on ne les gardes pas 

la commande utilisé est : git cherry-pick 84717a0 : elle permet de récupérer la commit 2 grace a sont ID on ne peux pas faire la méthode classique car il risque d'y avoir un conflit 

le V1.0.0 : 

1 : MAJOR : Version majeure, grosse mise a jour 
0 : MINOR : Version mineure, petite mise a jour 
0 : PATCH : Correctif de bug par exemple

une correction de bug mineur : 1.0.1
une nouvelle fonctionnalité compatible : 1.1.0
une refonte majeure incompatible : 2.0.0

QUESTIONS FINALS : 

1. 

2. Pour évité en cas de problème de casser la main 

3. 
- `git reset` réécrit l'historique
- `git revert` ajoute un nouveau commit

4. lorsque une fonctionnalité plus urgente et a réalisé 

5. en cas de conflit 

6. HEAD sert a retourner a un commit en arrière 

7. HEAD 2 permet de retourner a 2 commit en arrière 

8. a mettre un point de version 

9. ça facilite la maintenance car chaque etape est bien délimité 

10. il ne doivent pas etre versionner si ce sont des fichiers confidencielle avec des mots de passe comme le .env