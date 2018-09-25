# Grille d’évaluation Service API

Grille à utiliser pour évaluer le rendu du 7 octobre 2018.

  - Dans une évaluation binaire, `Ok` correspond au succès de l'étape considérée, `Ko` à son échec (pour quelque raison que ce soit);
  - Dans une évaluation graduée: 
    - les valeurs `A` et `B` sont au dessus de la moyenne;
    - les valeurs `C` et `D` sont en dessous de la moyenne;
    - la valeur `F` représente un échec (_Failure_), ou une absence d'information.

## Reproductibilité du déploiement

 - Documentation de l’environment technique 	
    - [A, B, C, D] | F
 - `./install.sh `
    - [Ok, Ko]
 - `docker-compose up` 
    - [Ok, Ko]
 - `./run.sh`	
    - [Ok, Ko]

## Couverture fonctionnelle

 - Cohérence de l’API avec la spec
     - [A, B, C, D] | F
 - Caractérisation des objets métiers			
     - [A, B, C, D] | F 
 - Qualité du scénario d’intégration			
     - [A, B, C, D] | F 

## Justesse de l’architecture
 - Styles utilisés correctement	
    - [A, B, C, D] | F
 - Capacité de passage à l’échelle du métier	
 	- [A, B, C, D] | F

## Justification des paradigmes

 - Argumentation des choix de conception		
     - [A, B, C, D] | F
 - Argumentation des choix de style
     - [A, B, C, D] | F
 - Description d’alternatives dans les ≠ styles
     - [A, B, C, D] | F
 - **Optionnel (bonus)**: Test de charge des services déployés
     - [A, B, C, D] | F

## Remarques sur les APIs développées.

_Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor. Cras elementum ultrices diam. Maecenas ligula massa, varius a, semper congue, euismod non, mi. Proin porttitor, orci nec nonummy molestie, enim est eleifend mi, non fermentum diam nisl sit amet erat. Duis semper. Duis arcu massa, scelerisque vitae, consequat in, pretium a, enim. Pellentesque congue. Ut in risus volutpat libero pharetra tempor. Cras vestibulum bibendum augue. Praesent egestas leo in pede. Praesent blandit odio eu enim. Pellentesque sed dui ut augue blandit sodales. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Aliquam nibh. Mauris ac mauris sed pede pellentesque fermentum. Maecenas adipiscing ante non diam sodales hendrerit._
