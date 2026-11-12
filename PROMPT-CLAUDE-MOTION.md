# Vidéo de démo Mire : brief pour Claude Motion

> Copiez tout ce fichier dans Claude Motion et joignez :
> - le plan vidéo `plan-camera-pov.mp4` ;
> - la photo `IMG_0511.jpg` ;
> - les dossiers `captures/`, `elements/` et `marque/`.
>
> Tout est réel : un vrai plan filmé sur un chantier, et les vrais écrans de l'application (données de démonstration cohérentes avec le plan filmé).

---

## Ce que je veux

Une vidéo de démonstration de **Mire**, une application de suivi de chantier pour les entreprises de **TP, VRD et réseaux**.
Public : dirigeants et conducteurs de travaux de PME du BTP. Ce sont des gens de terrain : ton direct et concret, pas de jargon startup.

**Format 1 (principal)** : 16:9, 1920×1080, environ 90 secondes.
**Format 2 (réseaux sociaux)** : 9:16, 1080×1920, environ 30 secondes (voir plus bas).

Style « motion design produit » :
- les écrans de téléphone sont placés dans un **cadre d'iPhone** ;
- les écrans d'ordinateur sont placés dans une **fenêtre de navigateur** épurée ;
- mouvements doux, **mise en évidence** des zones importantes (halo, cercle jaune, zoom) ;
- un texte court incrusté par scène ; transitions sobres.

## Charte graphique (obligatoire)

| Rôle | Couleur |
|---|---|
| Jaune engin, la couleur signature | `#F5B800` |
| Asphalte (fonds sombres, boutons) | `#1C1F23` |
| Craie (fonds clairs) | `#F4F3EF` |
| Texte | `#16181B` |
| Alerte (rouge) | `#C0262D` |
| Validé (vert) | `#0B6B66` |

Règles de la charte :
- le jaune se pose **uniquement sur fond sombre** (asphalte) ou sous un texte noir ;
- **jamais de texte jaune sur fond clair**, jamais de texte blanc sur jaune.

Polices :
- titres : **Archivo** (gras, légèrement étendu) ;
- textes : **Atkinson Hyperlegible Next** ;
- chiffres et mesures : **Atkinson Hyperlegible Mono**.

Logo, dans `marque/` :
- `mire-logo-horizontal.svg` sur fond clair ;
- `mire-logo-horizontal-negatif.svg` sur fond sombre ;
- `mire-symbole-jaune.svg` pour l'icône seule.

## L'histoire racontée (données de démo, toutes cohérentes)
- **Karim Benali**, chef de chantier, sur son téléphone.
- **Marc Lefort**, conducteur de travaux, au bureau sur ordinateur.
- Chantier : **« Eaux pluviales - lotissement Les Tilleuls »**.
- Ce qu'on filme : le **raccordement d'une descente d'eaux pluviales sur un tampon, au lot 12, le long de la façade**. Dans la tranchée, une **gaine électrique rouge passe juste au-dessus du raccord**. Elle n'est pas sur le plan : c'est l'alerte que Mire va relever.

---

## Script (format 16:9, environ 90 s)

### Scène 1 : l'accroche (0-7 s)
- **Visuel** : fond asphalte, texte en craie, mot « preuve » en jaune. En fond, très flouté : `IMG_0511.jpg`.
- **Texte incrusté** : « Trois mois après, un exploitant conteste. » puis « Où est la **preuve** ? »
- **Voix off** : « Trois mois après, un exploitant conteste. Où est la photo du raccord avant remblaiement ? »

### Scène 2 : l'interface du chef (7-14 s)
- **Visuel** : iPhone avec `captures/m01-chef-accueil.png`, puis glissement vers `captures/m02-chef-chantier-gestes.png`. Halo sur les 4 grosses tuiles. Le pouce touche la tuile noire **« Photo, appareil ou galerie »**.
- **Texte incrusté** : « Tout dans son téléphone. Même sans réseau. »
- **Voix off** : « Avec Mire, le chef de chantier a tout dans son téléphone. Quatre gestes, même au fond de la fouille, sans réseau. »

### Scène 3 : la photo, l'appareil s'ouvre et filme en direct (14-28 s)
**IMPORTANT :**
- `plan-camera-pov.mp4` est déjà monté. Il montre l'écran de l'iPhone pendant la prise de vue : l'appareil photo s'ouvre, la **vidéo réelle du chantier défile en direct** dans le viseur, le **déclencheur est pressé**, un **flash**, puis la photo file dans la vignette en bas à gauche.
- **Ne pas figer l'image avant la prise de vue** : on doit voir la vidéo en mouvement, puis seulement le déclenchement.
- Placer ce plan **tel quel dans l'écran de l'iPhone** (il a les proportions d'un écran d'iPhone : 786×1704). Ne pas le recadrer ni le ralentir.

Déroulé :
1. **Transition (0,5 s)** : depuis la tuile « Photo » touchée à la scène 2, l'écran de l'iPhone bascule sur `plan-camera-pov.mp4`.
2. **Le plan caméra (5 s)** : `plan-camera-pov.mp4` en entier, l'iPhone en grand au centre. Pendant le direct, un léger zoom avant sur l'iPhone.
3. **Retour dans Mire (5 s)** : `captures/m04-chef-photo-choix-etiquette.png` (barre verte « Photo enregistrée, un tag ? »), le pouce touche **« Avant remblaiement »**, puis `captures/m05-chef-photo-etiquette-choisie.png` (cercle jaune sur le bouton).
4. **Rangée (3 s)** : `captures/m03-chef-fil-du-chantier.png`. La photo, la même que celle qu'on vient de prendre, apparaît en haut du fil avec l'étiquette « Avant remblaiement » et « Karim Benali ».
- **Son** : ambiance de chantier en fond (gravier, pelle mécanique au loin), puis un **clic d'obturateur net** au moment du flash.
- **Texte incrusté** : « 1 photo = 1 preuve datée »
- **Voix off (narrateur)** : « Une photo, une étiquette. Elle est datée, rangée par chantier, avec son auteur. »

### Scène 4 : la note vocale, avec le son du chantier (28-50 s), le moment fort
- **Visuel** :
  1. **Le chef lance l'enregistrement (2 s)** : iPhone avec `captures/m06-chef-note-vocale-debut.png`, le pouce touche « Commencer l'enregistrement ». Derrière l'iPhone, en grand et flouté : la dernière image du chantier (`IMG_0511.jpg`), pour rester sur place.
  2. **Il parle (12 s)** : `captures/m07-chef-note-vocale-enregistrement.png` (micro rouge qui pulse, chrono qui défile). **On entend le chef**, avec le bruit du chantier derrière. En même temps, **la transcription s'écrit mot à mot** sous l'iPhone, sur un bandeau asphalte, en police Atkinson Hyperlegible, couleur craie, avec les mots importants en jaune : « lot 12 », « soixante centimètres », « gaine électrique rouge », « pas sur le plan ».
  3. **Il envoie (2 s)** : `captures/m08-chef-note-vocale-relecture.png` (titre « Raccord EP lot 12 »), le pouce touche **« Enregistrer la note »**. L'onde sonore se transforme en lignes de texte qui filent vers le haut.
  4. **Le résultat (6 s)** : `captures/m09-chef-note-transcrite-alerte.png`, ou en grand `elements/carte-note-vocale-alerte.png`. Zooms successifs sur :
     1. l'encadré rouge **« Alerte prioritaire : Réseau non répertorié : gaine électrique rouge au-dessus du raccord pluvial, absente du plan »** ;
     2. le badge **« Eaux pluviales »** et le relevé **« prof. 0,6 m · Lot 12, côté façade »** ;
     3. la **petite photo rattachée** à la note : c'est la photo prise à la scène 3 ;
     4. le résumé.
- **Son** :
  - pendant le passage 2 : **la voix du chef**, naturelle, un peu essoufflée, et l'ambiance du chantier en fond (environ 30 % du volume : gravier, pelle mécanique, bip de recul) ;
  - à partir du passage 3, l'ambiance baisse et la musique revient.
- **Ce que dit le chef**, mot pour mot (c'est exactement la transcription enregistrée dans l'application ; la transcription affichée doit être identique) :
  > « Lotissement Les Tilleuls, lot 12. Raccordement de la descente d'eaux pluviales sur le tampon, côté façade. C'est posé, le raccord est en place, on est à soixante centimètres. Attention : une gaine électrique rouge passe juste au-dessus du raccord, elle n'est pas sur le plan. On l'a laissée en place et protégée. Remblaiement demain matin. »
- **Texte incrusté** (après la transcription) : « Il parle. Mire écrit, relève… et alerte. »
- **Voix off (narrateur, sur le passage 4)** : « Mire transcrit, relève le réseau et la profondeur, rattache la photo… et repère l'anomalie : une gaine électrique absente du plan. »

### Scène 5 : le bureau est prévenu (50-62 s)
- **Visuel** : fenêtre navigateur avec `captures/d01-conducteur-accueil-alertes.png`. Halo rouge sur la ligne « Eaux pluviales - lotissement Les Tilleuls : Réseau non répertorié (Gaine électrique rouge au-dessus du raccord pluvial…) » du bloc « Alertes anomalies ». Puis glissement vers `captures/d04-conducteur-note-vocale-synthese.png`, avec un zoom sur « À faire : Signaler la gaine électrique hors plan… ».
- **Texte incrusté** : « Le conducteur est prévenu à l'instant. »
- **Voix off** : « Au bureau, le conducteur de travaux est prévenu au moment où c'est dit, avec la photo et l'action à mener. Plus d'anomalie oubliée entre deux appels. »

### Scène 6 : tout le chantier au même endroit (62-72 s)
- **Visuel** :
  - `captures/d03-conducteur-fil-chronologique.png` : défilement lent du fil (compte-rendu, note, photo) ;
  - puis `captures/d05-conducteur-filtre.png`, avec un clic sur « Documents » ;
  - puis `captures/d06-conducteur-documents-echeances.png` ;
  - en insert, `elements/carte-dict-echeance.png` avec le badge orange « À échéance · expire dans 3 jours ».
- **Texte incrusté** : « DICT, récépissés, arrêtés : avec leurs échéances. »
- **Voix off** : « Photos, notes, comptes-rendus, DICT et récépissés : tout le chantier au même endroit, dans l'ordre, avec les échéances. »

### Scène 7 : le rapport client (72-82 s)
- **Visuel** : `captures/d07-conducteur-rapport-pdf-pret.png`, puis les pages du rapport (`captures/r01-rapport-pdf-page1.png`, `captures/r02-rapport-pdf-page2.png`) qui se déploient en éventail. Zoom sur la photo du raccord dans le rapport.
- **Texte incrusté** : « Le rapport client en 1 clic. »
- **Voix off** : « En fin de semaine, le rapport PDF pour le client se génère en un clic, photos comprises. »

### Scène 8 : l'appel à l'action (82-90 s)
- **Visuel** : fond asphalte, logo négatif (`marque/mire-logo-horizontal-negatif.svg`) au centre. En arrière-plan, très flouté, la photo du raccord.
- **Texte incrusté** :
  - « Pour les équipes TP, VRD et réseaux » ;
  - **« Essai gratuit 14 jours, sans carte bancaire »** ;
  - **mirechantier.fr**, en jaune sur asphalte.
- **Voix off** : « Mire. Pour les équipes TP, VRD et réseaux. Essai gratuit de quatorze jours, sans carte bancaire, sur mirechantier.fr. »

---

## Format 2 : 9:16, environ 30 s
Le format vertical colle au plan filmé : l'écran du téléphone peut occuper presque toute l'image.
1. **(3 s)** Accroche « Où est la preuve ? » sur `IMG_0511.jpg` flouté.
2. **(6 s)** `plan-camera-pov.mp4` en plein cadre (direct, déclenchement, flash), puis l'étiquette « Avant remblaiement » (`m05`).
3. **(15 s)** Note vocale : `m07` avec la voix du chef, l'ambiance de chantier et la transcription mot à mot, puis la carte avec l'alerte rouge (`elements/carte-note-vocale-alerte.png`).
4. **(6 s)** Logo, « Essai gratuit 14 jours », mirechantier.fr.

Sous-titres incrustés en permanence : la majorité des gens regardent sans le son.

## Voix
- **Le chef** (scène 4) : voix d'homme, naturelle, un peu essoufflée, accent neutre, comme quelqu'un qui parle dans son téléphone au bord d'une tranchée. Texte mot pour mot plus haut.
- **Le narrateur** : voix française posée, débit naturel, proche du terrain (pas « pub radio »).
- Si la voix n'est pas possible, garde les textes incrustés et la transcription mot à mot : ils suffisent à comprendre.

## Sons
- Ambiance de chantier : gravier, pelle mécanique au loin, bip de recul.
- Clic d'obturateur au flash de la scène 3.
- Musique instrumentale discrète, à 10-15 % du volume sous les voix.

## À ne pas faire
- Figer la vidéo du chantier avant la prise de vue.
- Inventer des écrans ou des fonctions qui ne sont pas dans les captures.
- Modifier les textes de la transcription.
- Mettre du texte jaune sur fond clair.
- Afficher des prix (ils peuvent changer).
