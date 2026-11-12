# Crédits

## Modèles 3D

| Dossier              | Pack                                   | Auteur     | Licence                                                    |
| -------------------- | -------------------------------------- | ---------- | ---------------------------------------------------------- |
| `jeu/assets/nature`  | Stylized Nature MegaKit (version Standard) | Quaternius | CC0 1.0 (domaine public) — `jeu/assets/nature/LICENSE.txt`  |
| `jeu/assets/village` | Medieval Village MegaKit (version Standard) | Quaternius | CC0 1.0 (domaine public) — `jeu/assets/village/LICENSE.txt` |
| `jeu/assets/animaux` | Poule, mouton, biche, loup, moustique géant, lapin, abeille, écureuil, renard, hérisson | TamagoChoupie (générés par `jeu/outils/dragon/generer_animaux.py`) | MIT — `jeu/assets/animaux/LICENSE.txt` |
| `jeu/assets/son` | Musiques d'orchestre (cordes, violoncelle, piano, harpe, cor), pluie, éclaboussure et clapotis | TamagoChoupie (composées par `jeu/outils/son/generer_musique.py`) | MIT — `jeu/assets/son/LICENSE.txt` |
| `jeu/assets/son/cri_*.wav` | Cris de Choupie : glapissement du bébé, cri de l'ado, rugissement de l'adulte (création originale, aucun échantillon tiers) | TamagoChoupie (composés par `jeu/outils/son/generer_cris.py`, description dans `cris.json`) | MIT — `jeu/assets/son/LICENSE.txt` |
| `jeu/assets/voix` | Voix enregistrées des personnages (fichiers `<id_de_replique>.ogg`, ajoutés au fil de l'enregistrement) | Lucas Tuzi (auteur du jeu) | MIT — `jeu/assets/voix/LICENSE.txt` |
| `jeu/assets/bruitages` | Bruitages de l'île : pas selon la surface, atterrissage, froissement des herbes, vent, ressac, ruisseau, oiseaux (recadrés et filtrés par `jeu/outils/son/preparer_bruitages.py`, origine de chaque fichier dans `bruitages.json`) ; grillons synthétisés | Kenney (« Impact Sounds », « RPG Audio », https://kenney.nl) et Pixel-boy & AAA (« Ninja Adventure », https://pixel-boy.itch.io/ninja-adventure-asset-pack) | CC0 1.0 (domaine public) — `jeu/assets/bruitages/LICENSE.txt` |
| `jeu/assets/calinounou` | Calinounou, la licorne en peluche compagne de Choupie (d'après la peluche de Lucas) | TamagoChoupie (générée par `jeu/outils/dragon/generer_calinounou.py`) | MIT — `jeu/assets/calinounou/LICENSE.txt` |
| `jeu/assets/cinematique` | Bruitages de la cinématique d'ouverture : tonnerre et grondement d'orage, pluie battante, rivière, cascade, mer, œuf qui roule, plongeons (recadrés, filtrés et mêlés par `jeu/outils/son/preparer_cinematique.py`, origine de chaque fichier dans `cinematique.json`) | Pixel-boy & AAA (« Ninja Adventure », https://pixel-boy.itch.io/ninja-adventure-asset-pack) et Kenney (« Impact Sounds », https://kenney.nl) | CC0 1.0 (domaine public) — `jeu/assets/cinematique/LICENSE.txt` |
| `jeu/assets/gigi` | Gigi, la grenouille en peluche de la vieille maison, et son bébé canard Fifi (d'après les peluches de Lucas) | TamagoChoupie (générés par `jeu/outils/dragon/generer_gigi.py`) | MIT — `jeu/assets/gigi/LICENSE.txt` |
| `jeu/assets/amies` | Lili, la chienne de Lucas, et Petit chat, sa chatte (d'après les photos de leurs animaux) ; petit aboiement de Lili (`aboiement.wav`, adouci) | TamagoChoupie (modèles générés par `jeu/outils/dragon/generer_amies.py`) ; aboiement : Pixel-boy & AAA (« Ninja Adventure », https://pixel-boy.itch.io/ninja-adventure-asset-pack) | Modèles : MIT ; aboiement : CC0 1.0 — `jeu/assets/amies/LICENSE.txt` |
| `jeu/assets/choupie` | Choupie, le bébé dragon | TamagoChoupie (généré par `jeu/outils/dragon/generer_dragon.py` ; œil « peluche » du bébé `oeil_bebe_doux.png` par `generer_oeil_bebe.py`) | MIT, comme le code du projet — `jeu/assets/choupie/LICENSE.txt` |
| `jeu/assets/choupie` | Choupie, le bébé dragon | TamagoChoupie (généré par `jeu/outils/dragon/generer_dragon.py` ; œil « peluche » du bébé `oeil_bebe_doux.png` par `generer_oeil_bebe.py` ; yeux bleus `oeil_choupie_*.png` par `generer_oeil_choupie.py`) | MIT, comme le code du projet — `jeu/assets/choupie/LICENSE.txt` |
| `jeu/assets/sol` | Textures du sol : herbe, terre, sable, roche (couleur et relief) | TamagoChoupie (générées par `jeu/outils/sol/generer_textures.py`) | MIT — `jeu/assets/sol/LICENSE.txt` |

Source : https://quaternius.com. Seuls les modèles utilisés par le jeu sont conservés ; leurs textures ont été
réduites à 1024 px pour les téléphones.

Choupie, Calinounou, Gigi, Fifi, Lili, Petit chat et les animaux de l'île sont modélisés par code (volumes lisses, squelette, yeux texturés) : aucun modèle
tiers pour les personnages.

## Code, sons, interface

Écrits pour TamagoChoupie : Choupie, les animaux (modèles, squelettes et animations), la musique et les cris sont générés
par code ; les bruitages de l'île viennent de packs CC0 (voir le tableau).
