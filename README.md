# La bibliothèque des médias Evarisk
Vous trouverez dans ce dossier :
Les médias utilisés par Evarisk et DigiRisk
Des exemples de causeries sécurité

publié sous licence MIT

##  Organisation des fichiers

### Fichiers sources

les fichiers sources doivent être rangés dans le dossier "famille". Les fichiers sources sont souvent au format natif(Ai, EPS, Odt, PSD....)

Le nommage du fichier source et des exports doivent respecter la charte de nommage suivante :
* Les caractères autorisés sont [a-z],[1-9]
* famille_sousfamille_motscles_resolution.ai
* les valeurs pour "resolution" sont : "source" ou "150px" ou "300px"

Exemple "sans motscles" :
* risque_ambiances-lumineuses_source.ai
* risque_ambiances-lumineuses_150px.png
* risque_ambiances-lumineuses_300px.png

### Exports des fichiers
2 exports doivent être réalisés au format png en suivant les consignes suivantes : 
* Couleur CMJN ou RVB 
* Taille est pilotée par la largeur
* Le premier en résolution de 150px; le deuxième en résolution de 300px

## Charte de nommage
### Noms des familles récurrents
Les noms ci-dessous sont "récurrents", on considère que leur utilisation est courante. Le but étant de pouvoir retrouver facilement les illustrations par famille, sous-famille et/ou mots clés.

* causerie
* danger
* epi
* homme
* materiel
* methode 
* risque

### Noms des sous familles récurrrents

#### Famille : causerie
Les noms choisis sont basés sur les catégories de risques du document ED840.pdf de l'INRS. On peut le trouver dans le dossier : \causerie\_modele-causerie\listing_risque.txt

Le dossier _modele-causerie vous permet d'avoir un exemple des modeles de causerie afin que l'import puisse être automatique dans DigiRisk. Il faudra :
Fichier d'import des textes : _causerie_modele-slide.txt
Fichier des médias sources : _causerie_modele-slide.odp
Fichier médias à importer : _causerie_modele-slide_media1.jpg etc...


#### Famille : danger
à venir

#### Famille : epi

* casque
* gant
* lunette
* vetement

#### Famille : homme

* charge-lourde
* allergie
* ambiances-lumineuses
* blessures
* bruit
* burnout
* changement-entreprise
* charge-lourde
* metiers
* chute
* effrondrement
* electricite
* incendie
* info
* intoxication
* juge
* organisation-lieu-travail
* psychocial
* rayonnement

#### Famille : materiel

* outils

#### Famille : risque
Les noms seront aussi choisis sont basés sur les catégories du document ED840 de l'inrs.
On peut trouver les familles dans le dossier : \causerie\_modele-causerie\listing_risque.txt

### Mots clés

Les mots clés sont laissés libres, en respectant les caracères imposés: [a-z],[1-9], faites vous plaisir par exemple :

* masque
* armoire
* etc
