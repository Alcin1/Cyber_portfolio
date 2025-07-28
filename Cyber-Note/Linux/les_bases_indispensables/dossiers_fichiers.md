## SE DEPLACER
- cd = se déplacer d'un fichier à l'autre  
![1c](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/Screenshot%202025-07-24%20110042.png?raw=true)
![2c](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/Screenshot%202025-07-24%20110705.png?raw=true)
- cd ~ = revenir à l'endroit de base( le début de l'arborescence)  
![~](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/Screenshot%202025-07-24%20110756.png?raw=true)
- cd .. ou cd ../.. = revenir en arrière (tout dépend de combien)  
![cd..](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/Screenshot%202025-07-24%20110756.png?raw=true)
- find /…/… -name = trouver fichier avec chemin
- find / -name "..." 2>/dev/null = trouver fichier sans chemin juste avec le nom ( 2>/dev/null permet de ne pas avoir les chemins d'erreur)
- grep [ce que tu veux chercher] [où chercher]  
![g](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/imtage.png?raw=true)

## CREATION ET SUPPRESSION
- mkdir = créer un dossier    
![1](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/1.png?raw=true)
- rmdir = supprimer un dossier  
![2](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/2.png?raw=true)
- touch = créer un fichier   
![3](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/3.png?raw=true)
- rm = supprimer un fichier  
![4](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/4.png?raw=true)
- rm -rvf = supprimer un dossier et son contenu ( grâce à l'option -r, -v > sa liste le contenu effacer, f pour force  )

## ACTION SUR LE FICHIER
- cat = voir fichier    
![c](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/Screenshot%202025-07-24%20110837.png?raw=true)
- nano = modifier un fichier  
  ![5_a](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/5_2.png?raw=true)
  ![5](https://github.com/Alcin1/Cyber_portfolio/blob/main/Cyber-Note/Linux/les_bases_indispensables/image/5_1.png?raw=true)
- cp [source] [destination] = cloner un fichier
- mv [source] [destination] = déplacer un dossier/fichier (si on met l'ancien nom comme source et le nouveau comme destination, cela le renomme)
