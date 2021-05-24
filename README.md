# nan_projet5
#################### exo 1 #####################

"""
Remplacer un mot par un autre Dans cet exercice, 
vous devez remplacer le mot "Bonjour" dans la variable 
phrase par le mot "Bonsoir"  Ã  l'aide d'une 
mÃ©thode disponible sur les chaÃ®nes de caractÃ¨res. 
La variable nouvelle phrase devra donc 
contenir la chaÃ®ne de caractÃ¨res "Bonsoir tout le monde."

"""
```python
phrase = "Bonjour tout le monde."
nouvelle_phrase =phrase.replace('Bonjour', 'Bonsoir')
### exo 2
"""
Compter le nombre d'occurrences d'une lettre dans une phrase 
Dans cet exercice, nous cherchons Ã  compter le nombre d'occurrences 
d'une lettre dans une chaÃ®ne de caractÃ¨re. Ici, nous cherchons 
le nombre de fois que la lettre "o" apparaÃ®t dans la phrase 
"Bonjour tout le monde"
Votre script devra retourner dans ce cas-ci 
dans une variable rÃ©sultat le nombre 4 !
"""


lettre_a_chercher = "o"
phrase = "Bonjour tout le monde"
resultat = phrase.count(lettre_a_chercher)


##################### exo 3 ####################

"""
Dans cet exercice, le but est de compter le nombre de phrases 
prÃ©sentes dans le texte contenu dans la variable lorem Ce texte 
contient 4 phrases, votre script devra donc retourner le nombre 4 
dans la variable resultat

Astuce : pensez Ã  ce qui dÃ©finit une phrase. Une majuscule et un... ?
"""


lorem = """Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
		   Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
		   Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
		   Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."""
## print("exo 3")
car='.'
nc=0
i=0
while i <len(lorem):
     if lorem[i]==car:
          nc=nc +1
     i=i+1
#print(nc)

##################### exo 4 ####################
"""
Le but de cet exercice est de remettre en ordre alphabÃ©tique 
les prÃ©noms prÃ©sents dans la chaÃ®ne de caractÃ¨re. Vous devez 
crÃ©er une variable chaÃ®ne en ordre qui, Ã  la fin de l'exercice, 
doit contenir la chaÃ®ne de caractÃ¨re suivante :"Anne, Julien, Lucien, Marie, Pierre" 
Pour trier une liste, on utilise la mÃ©thode sort. 
Par exemple :Pour le reste de l'exercice, 
vous devrez utiliser la mÃ©thode split et la 
mÃ©thode join que l'on a vu dans ce chapitre. 
N'allez pas chercher trop complexe, la solution tient en 3 lignes! 
Veillez Ã  bien respecter les virgules et les espaces pour valider 
l'exercice
"""
  


chaine = "Pierre, Julien, Anne, Marie, Lucien"
chaine = chaine.split()
chaine= sorted(chaine)
chaine=  " ".join(chaine)
print(chaine)
```
