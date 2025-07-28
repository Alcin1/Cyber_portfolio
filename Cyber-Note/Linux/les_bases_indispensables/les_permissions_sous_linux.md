## LISTER LES UTILISATEURS 
- cat /etc/passwd = voir tout les users
- sudo cat /etc/shadow = voir les mp des users en hacher
- cat /etc/group = voir les grps
- cat /etc/gshadow =  voir les mp des grps en hacher

## CREATE AND DELETE USERS/GRPS
- sudo adduser [name] = créer un user
- sudo deluser[name] = supprimer un user
- su[name] = changer de user
- passwd [name] = change mp du user
- sudo addgroup [name] = créer un grp
- sudo delgroup [name] = supprimer un grp
- Déplacer un utilisateur dans un grp

|sudo addgroup   | [user]      | [group]   |
|---|---|---|

- id [name] = voir uid et gid

## PERMISSIONS
- d~~~~~~ = dossier  
- l~~~~~~ = lien symbolique

- rwxr--r--
  
| rwx | rw- | r-- |
|---|---|---|
| propriétaire| groupe propriétaire | les autres |

  r = read 
  w =  write 
  x = execute 
- chmod u-r test.txt

| chmod | permissions | fichier |
|---|---|---|  

| u | user/proprio |
|---|---|
| g | groupe |
| o | les autres |
| a | tout le monde |
| + | ajoute |
| - | enlève |  

- chown [user:groupe] [fichier] = changer le propriétaire du groupe
