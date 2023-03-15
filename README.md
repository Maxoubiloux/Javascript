Notes
=====

## Type de casse

Camel case : maVariable
Pascal case : MaVariable

Pour écrire un commentaire on utilise :

```
// Ceci est un commentaire
```

## Variables

Pour créer des variables globales, le nom des variables sont sensibles à la casse :

```
var maVariable
```

Variable valable uniquement dans le bloc en cours :

```
let maVariable
```
**Aucun var dans le code, utiliser let et const**

## Se développer

Apprendre les langages de base
Se spécialiser mais rester aware des autres technologies
Se focaliser sur des langages que l'on aime

## Assignation et égalité

Égalité (comparaison stricte) : 

```
===
```

Assignation : 

```
=
```

Inégalité : 

```
!==
```

Supérieur ou égal/inférieur ou égal : 

```
>== / <==
```

## Autres

Parcourir le tableau rapidement :

```
for (value)
```
```
let function = (a, b) => {

}
```
ou
```
setTimeout(

    function() {
        console.log('Hello world!');
    }
,
1000(en ms));
```

## Commande Git

Vérifier le statut des fichiers :
```
git status
```

Ajouter des fichiers dans les fichiers à sauvegarder :
```
git add "nom_dossier" (. ou * pour tout)
```

Sauvegarder le fichier :
```
git commit
```

Sauvegarder un fichier sans VIM :
```
git commit -m "message de commit"
```