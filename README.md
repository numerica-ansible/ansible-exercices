# ansible-exercices
Ecrire un playbook ```play-vars.yml``` permettant d’afficher le nom de la distribution de la cible ainsi
que sa version majeure, en utilisant des variables globales 
Pour trouver la variable  

```ansible alpine -m setup | grep "distribution"```
