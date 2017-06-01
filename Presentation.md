
# Presentation du projet : Limites de contrôles

## Auteur : Laurent Cesaro

###### Technologies utilisées :
* TIBCO Spotfire
* Python
* R

###### Objectifs :

Le but de ce projet est de récupérer le moteur de calculs des
limites de contrôles codé en R. Puis utiliser le logiciel de Business
Intelligence Spotfire et d’y implémenter le moteur de calcul.

La deuxième partie est la réalisation d'une application sur Spotfire sous forme de "line story" afin qu'elle soit souple et simple d'utilisation.

###### Limites de contrôles

Les limites de contrôles permettent de déterminer le moment où apparaît une cause particulière de variation d'une caractéristique, entraînant une altération du processus.


![ScreenShot](CL.PNG)

### Description de l'application

Le projet c’est divisé en 2 sous projets. Un premier projet
a été réalisé avec les données issue de l’usine de Crolles 200mm et un deuxième
avec les données de l’usine Crolles 300mm.

Chaque sous projet se divise en 2 parties. Une partie calcul
des limites de contrôles et une partie visualisation des limites de contrôles
qui sont déjà présentes en base de données.

![ScreenShot](ShApplication.PNG)

#### Etape 1 : Développement d'un menu
Afin que l'utilisateur puisse se déplacer dans l'application, il a fallu créer un menu qui est présent dans toutes les pages. 
Il a été développé en HTML, CSS et JavaScript.

![ScreenShot](menu.PNG)

#### Etape 2 : Sélection des doonées
Présenté dans une table, l'utilisateur peut sélectionner des données qui lui serviront à charger de nouvelles données qui seront nécessaire aux calculs.

![ScreenShot](CharData.PNG)
