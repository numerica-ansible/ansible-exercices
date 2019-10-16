# ansible-exercices
Ecrire un playbook ```play-vars.yml``` permettant d’afficher le nom de la distribution de la cible ainsi
que sa version majeure, en utilisant des variables globales 
Pour trouver la variable  

```ansible alpine -m setup | grep "distribution"```

Creer une variable locale nommee port_http contenant la valeur 8080. Utiliser cette variable
dans un message

Créer une variable nommee service de type dictionnaire avec comme :
```yaml
service:
  name: apache
  rpm: httpd
```
Etudier les scripts    
 play-variables.yml  
 play-variables-dict.yml  
et play-variables-surcharge  
et passer le parametres extra-vars  
```ansible-playbook -i ../inventory_children --extra-vars "type=db" play-variables-surcharge.yml```
