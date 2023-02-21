
<link rel="stylesheet" href="css/style.css">  
  
# TP1 – Carrousel - Grille d’auto-évaluation
ma note = __[ XX ]__ sur 10, vaut pour 5% de la session  
  
## Critères
## 1. Balisage sémantique et structurel    
[2 points] 

__Sous-critère 1__ [ + 0.5 ] si réussi ma note = __[ X.X ]__  
- Le code HTML a été validé à l’aide du validateur du w3c   
Déposer dans le dossier images une capture-écran du résultat de validation initiale.    
[Validation initiale](images/capture1.png)    

__Sous-critère 2__ [ + 1.5 ] si réussi ma note = __[ X.X ]__
- Le code HTML a été corrigé puis revalider à l’aide du validateur du w3c   
Déposer dans le dossier images une capture-écran du résultat de validation finale.  
[Validation finale](images/capture2.png)   

__Sous-critère 3__ [ + :unicorn: ]  
- Balisage sémantique... 
Il n'y a pas d'outil pour vérifier si le choix des balises et des attributs est bien fait...  
N'hésitez pas à vérifier dès que vous avez un doute et... essayez d'avoir toujours des doutes :laughing:. 



## 2. Utilisation adéquate et créative de Google Fonts 
[1 point] 
  
__Sous-critère 1__ [ + 0.25 ] = ma note __[ X.XX ]__  
- Dans le dossier de départ, le dossier polices a été supprimé.    
Les instructions @font-face ont été effacées du fichier typo.css puisque nous avons décidé d'utiliser l'API de Google Fonts. Cette API utilise un mouchard pour vérifier quel format de police (woff2, woff ou ttf) est le plus adapté à l'appareil du visiteur et elle génère une instruction @font-face pour télécharger la police. 

__Sous-critère 2__ [ + 0.25 ] = ma note __[ X.XX ]__
- Sur *Google Fonts*, un choix d'au minimum 2 polices ou 2 variantes d'une même police a été fait.  
L'instruction `@import` pour télécharger ces polices a été ajouté au début du fichier style.css  

__Sous-critère 3__ [ + 0.5 ] = ma note __[ X.XX ]__
- Les polices s'appliquent bien.    
Des variables dans le fichier utilitaires.css contiennent les noms des polices.  
Dans le fichier typo.css, les valeurs de la propriété ```font-family``` utilisent les variables.  


## 3. Styles CSS 
__Les bases : importation correcte des fichiers normalize, utilitaires, typo et optionnellement grille.css, utilisation des variables, présence bien définie et harmonieuse d'un bandeau d'entête et d'un pied de page__   
[2 points]  
  
__Sous-critère 1__ [ + 0.5 ] = ma note __[ X.XX ]__
- La liste des variables du fichier __utilitaires.css__ a été modifiée et les variables
sont utilisés dans les fichiers typo et style.css

__Sous-critère 2__ [ + 0.5 ] = ma note __[ X.XX ]__
- Dans le fichier __typo.css__ : 
    - les polices utilisées pour les titres h1-h6 et pour le corps du document sont définies par des variables.
    - la taille des titres h1-h6 est en rem et varie selon la largeur de l'écran.

__Sous-critère 3__ [ + 1 ] = ma note __[ X.XX ]__
- Les styles sont développés *Mobile First* dans le fichier __style.css__.
Les requêtes media sont placées comme variantes tout de suite après chaque sélecteur. 


## 4. Choix des images, optimisation et présence des crédits 
[1 point]  

__Sous-critère 1__ [ + 0.25 ] = ma note __[ X.XX ]__
- Il y a bien 7 images sur le même sujet. 

__Sous-critère 2__ [ + 0.5 ] = ma note __[ X.XX ]__
- Les images ont été redimensionnées et optimisées.
Elles ont un poids de moins de 250ko.  

__Sous-critère 3__ [ + 0.25 ] = ma note __[ X.XX ]__
- Chaque image est accompagné de son crédit comportant un lien vers l'auteur et le site de la banque d'images.   

## 5. Stratégie d’intégration complétée 
[1 point]
  
__Sous-critère 1__  [ + 0.5 ] = ma note __[ X.XX ]__
Avoir pris le temps d'esquisser la mise en page et figurer, tracer les conteneurs de blocs et de rangées requis pour obtenir cette mise en page.   
[photo de la mise en page esquissée](images/mise-en-page.jpg)  

__Sous-critère 2__  [ + 0.25 ] = ma note __[ X.XX ]__
Avoir pris le temps d’identifier les conteneurs sémantiques utiles dans le HTML avant d’ajouter
des div et des span.  

__Sous-critère 3__  [ + 0.25 ] = ma note __[ X.XX ]__
Utiliser l'inspecteur de code dans le navigateur OU le __pliage de code__ dans l'éditeur pour bien visualiser la relation parent-enfants entre les conteneur Flex et leurs items.  


## 6. Défis 
[2 points] 

### Expliquer brièvement votre défi et compléter la section A ou B
________________
________________
________________
________________

| A | B |
|---|---|
| __A. Mise en page plus élaborée__ | __B. Amélioration des fonctionnalités__ |
| La mise en page est fluide, mono-colonne sur l’écran étroit et enrichie sur l’écran large. | Une fonctionnalité a été ajoutée au carrousel et celui-ci demeure accessible sans JavaScript. |
| Documenter par 2 captures écrans. | Documenter par 2 captures écrans. |
| [Écran étroit](images/capture3.png) | [Avec JavaScript](images/capture3.png) |
| [Écran large](images/capture4.png) | [Sans JavaScript](images/capture4.png) |

Barème:
- non réalisé  [ + 0 ] 
- débuté mais inachevé [ + 1 ] 
- moyennement fière/fier du résultat [ + 1.2 ] 
- plutôt fière/fier du résultat [ + 1.7 ] 
- fière/fier du résultat [ + 2 ] 

__= ma note [ X.XX ]__

## 7. Versionnage 
[1 point] 

__Sous-critère 1__  [ + 1 ] = ma note __[ X.XX ]__
- Avoir versionné au moins une étape préalable avant la remise finale.  
- Documenter l'historique des commits par une capture écran:    
[Historique (exemplaire) à remplacer par le vôtre](images/capture5.png)

## 8. Bonus
[+ 0.5 point] 

__Sous-critère 1__  [ + 0.5 ] = ma note __[ X.XX ]__
- Avoir complété cette autoévaluation :muscle: :muscle: :muscle: