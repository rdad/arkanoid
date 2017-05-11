# Arkanoid
### jeux web en solo

C’est un casse-brique futuriste où le joueur doit détruire toutes les briques pour passer au niveau suivant. Des combos spectaculaires pimentent la progression.

![wireframe](https://thumb.ibb.co/hrdamQ/arkanoid_screenshot.jpg "wireframe 1")

## REGLES

* L’utilisateur contrôle la raquette avec les touches fléchées
* La balle se déplace en suivant les règles physiques sans gravité et rebondit sur la raquette, les briques et les murs
* Les briques disparaissent quand elles sont percutées par la balle
* Chaque brique détruite augmente le score 10 points
* Quand une brique est détruite, il y a 10% de chance qu'un combo tombe de cette position
* Quand toutes les briques sont détruites, on change de niveau et le joueur gagne niveau*10 points

## TECHNOLOGIES

Jeux développé en Javascript, avec Phaser comme moteur principal.
Le _board_ des meilleurs scores est enregistrés sur un serveur web standard, avec PHP et une base de données mySQL

## DATAS

#### Niveau 1

Briques 10 x 3 au centre
Combo : 2 balles

#### Niveau 2

Briques : 2 carrés de 5 x 3
Combo : 2 raquettes

