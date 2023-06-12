# HN_Python_Projet1

# Description
Dans le cadre du cours Python (enseignant [Chahan Vidal-Gorène ](http://cv.hal.science/chahan-vidal-gorene)) du [Master Humanités Numériques de l'ENC ](https://www.chartes.psl.eu/fr/rubrique-admissions/master-humanites-numeriques), nous rassemblons dans ce dépôt les documents référents au travail de l'équipe du projet 1 : détection et classification d'enluminures.

# Données
Données : enluminures extraites du Ministère de la Culture [Plateforme Ouverte du Patrimoine](https://www.pop.culture.gouv.fr/search/list?base=%5B%22Enluminures%20%28Enluminures%29%22%5D&image=%5B%22oui%22%5D)
Logiciel d'annotation : [VGG Image Annotator (VIA) ](https://www.robots.ox.ac.uk/~vgg/software/via/)

## Detectron 2

Source code : https://github.com/facebookresearch/detectron2

```bash
conda create --name detectron2 python=3.8
git clone https://github.com/facebookresearch/detectron2.git
python -m pip install -e detectron2
python -m pip install detectron2 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu111/torch1.8/index.html
pip install ipykernel
```

## Rendez-vous
- 16/03 [CR](https://github.com/carolisteia/HN_Python_Projet1/blob/main/CR/CR_10mars)
- 06/04 [CR](https://github.com/carolisteia/HN_Python_Projet1/blob/main/CR/CR_6avril)
- 08/06 Rendez-vous final

# Éléments présent dans le dépôt
- `CR/` : dossier contenant les comptes rendus des rendez-vous de groupe
- `json/` : dossier contenant les json de nos annotations
- `notebooks/`: dossier contenant les notebook Detectron2
- `Python_HN/`: dossier contenant le notebook final Detectron2, le répertoire contenant les images, les annotations finales et les résultats du modèle.
- `parametres_VGG.png` : capture d'écran des paramètres utilisés sur VGG pour les annotations 'humain'. 

# Membres de l'équipe
- Noé Leroy *alias* apogonoe
- Colin Prudhomme *alias*  MightyPotato9
- Lise Bernard *alias* lisebernard
- Carolina Macedo *alias* carolisteia
- Ekaterina Iakovlena *alias* yavlenieraket
- Fengyi Chen *alias* fychen11
- Yaelle Zribi *alias* yaelle-z

