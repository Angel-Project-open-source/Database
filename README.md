# Comment utiliser?
Voici les fonctions
## add
```py
add(Data, collection)
```
### Ajouter une valeure
```py
add({"_id": "701089274309812739801273", "Tax" false}, 'taxes')
```
### Modifier une valeure
```py
add({"_id": "701089274309812739801273", "Tax": true}, 'taxes')
```
La préscision de si on doit ajouter ou modifier est automatique
### Supprimer
```py
delete(Id, collection)
```
```py
delete("701089274309812739801273", 'taxes')
```
### Search
```py
search(id, collection)
```
```py
search("701089274309812739801273", 'taxes')
```
