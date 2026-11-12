# Vidéo de démo Mire : brief pour Claude Motion

> Copiez tout ce fichier dans Claude Motion et joignez les dossiers `captures/`, `elements/` et `marque/`.
> Les captures sont de vrais écrans de l'application, avec des données de démonstration.

---

## Ce que je veux

Une vidéo de démonstration de **Mire**, une application de suivi de chantier pour les entreprises de **TP, VRD et réseaux** (pose de canalisations, assainissement, réseaux secs).
Public : dirigeants et conducteurs de travaux de PME du BTP. Ce sont des gens de terrain : ton direct et concret, pas de jargon startup.

**Format 1 (principal)** : 16:9, 1920×1080, environ 90 secondes.
**Format 2 (réseaux sociaux)** : 9:16, 1080×1920, environ 30 secondes, avec les sous-titres incrustés (scènes 1, 3, 4 et 8 seulement).

Style « motion design produit » :
- les captures téléphone sont placées dans un **cadre d'iPhone** ;
- les captures ordinateur sont placées dans une **fenêtre de navigateur** épurée ;
- mouvements doux (zoom lent, glissements), **mise en évidence** des zones importantes : halo, cercle jaune, zoom ;
- un texte court incrusté par scène ; transitions sobres. Pas d'effets gadgets.

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

Fichier complet des couleurs : `marque/mire-tokens.json`.

## Les personnages (données de démo)
- **Karim Benali**, chef de chantier : sur son téléphone, sur le terrain.
- **Marc Lefort**, conducteur de travaux et dirigeant : au bureau, sur ordinateur.
- Chantier : **« Renouvellement réseau AEP - rue des Lilas »** (remplacement d'une conduite d'eau potable).

---

## Script (format 16:9, environ 90 s)

### Scène 1 : l'accroche (0-8 s)
- **Visuel** : fond asphalte. Le texte apparaît en grand, en craie, avec le mot « preuve » en jaune. En fond, très léger et flouté : `elements/vrd-tranchee-ouverte.jpg`.
- **Texte incrusté** : « Trois mois après, un exploitant conteste. » puis « Où est la **preuve** ? »
- **Voix off** : « Trois mois après, un exploitant conteste. Où est la photo de la tranchée avant remblaiement ? »

### Scène 2 : le chef de chantier (8-16 s)
- **Visuel** : iPhone avec `captures/m01-chef-accueil.png`, puis glissement vers `captures/m02-chef-chantier-gestes.png`. Halo sur les 4 grosses tuiles : Photo, Dicter une note, Document, Compte-rendu.
- **Texte incrusté** : « Tout dans son téléphone. Même sans réseau. »
- **Voix off** : « Avec Mire, le chef de chantier a tout dans son téléphone. Quatre gestes, même au fond de la fouille, sans réseau. »

### Scène 3 : la photo, vue à la première personne (16-32 s)
On voit **par les yeux du chef de chantier** (vue POV) : ses mains tiennent l'iPhone devant une tranchée ouverte.
- **Visuel** :
  1. **POV terrain (3 s)** : plan en caméra à l'épaule, léger tremblé naturel. Une tranchée ouverte, une conduite bleue (PEHD) posée sur un lit de sable, des cônes de chantier, une pelle mécanique au loin. Lumière de fin d'après-midi. Une main gantée tient l'iPhone, écran face à nous.
  2. **L'appareil photo s'ouvre (3 s)** : sur l'écran de l'iPhone, l'interface de l'appareil photo (superposer `elements/viseur-camera-iphone.png` sur l'image filmée). Dans le viseur : la même tranchée, cadrée sur la conduite. Le pouce appuie sur le déclencheur.
  3. **Déclenchement (1 s)** : petit flash blanc et son d'obturateur. L'image se fige et se rétrécit vers le bas de l'écran. Pour l'image figée, utiliser `elements/vrd-avant-remblaiement.jpg` : c'est la photo retrouvée ensuite dans l'application.
  4. **Retour dans Mire (5 s)** : iPhone avec `captures/m04-chef-photo-choix-etiquette.png`, zoom sur la barre verte « Photo enregistrée, un tag ? » ; le pouce touche **« Avant remblaiement »** (`captures/m05-chef-photo-etiquette-choisie.png`, cercle jaune).
  5. **Rangée (4 s)** : `captures/m03-chef-fil-du-chantier.png`, la photo apparaît dans le fil avec l'étiquette « Avant remblaiement » et « 17h30 · Karim Benali ».
- **Son** : ambiance de chantier en fond (moteur de pelle mécanique au ralenti, bip de recul lointain, pas sur le gravier), puis le « clic » de l'obturateur, bien net.
- **Texte incrusté** : « 1 photo = 1 preuve datée »
- **Voix off (narrateur)** : « Une photo, une étiquette. Elle est datée, rangée par chantier et par rue, avec son auteur. »

### Scène 4 : la note vocale, avec le vrai son du chantier (32-52 s), le moment fort
- **Visuel** :
  1. **POV (3 s)** : toujours par les yeux du chef. Il relève l'iPhone vers sa bouche, la tranchée en arrière-plan et le fourreau orange visible au fond de la fouille. À l'écran : `captures/m06-chef-note-vocale-debut.png`, le pouce touche « Commencer l'enregistrement ».
  2. **Il parle (8 s)** : à l'écran, `captures/m07-chef-note-vocale-enregistrement.png` (micro rouge qui pulse, chrono qui défile). **On entend le chef parler**, avec le bruit du chantier derrière (voir le texte plus bas). En même temps, **les mots apparaissent un à un** en sous-titre, comme une transcription en direct, en police Atkinson Hyperlegible, sur un bandeau asphalte.
  3. **Envoi (2 s)** : `captures/m08-chef-note-vocale-relecture.png`, le pouce touche « Enregistrer la note ». Une petite animation « envoi » : l'onde sonore se transforme en lignes de texte qui filent vers le haut.
  4. **Le résultat (7 s)** : `captures/m09-chef-note-transcrite-alerte.png`, ou en grand `elements/carte-note-vocale-alerte.png`. Zooms successifs sur :
     1. l'encadré rouge **« Alerte prioritaire : Réseau non répertorié »** ;
     2. la ligne de relevé **« PEHD · Ø110 mm · prof. 1,2 m »** ;
     3. le résumé.
- **Son** :
  - pendant le passage 2 : **la voix du chef**, naturelle et un peu essoufflée, avec en fond, à environ 30 % du volume, l'ambiance du chantier (moteur de pelle, chocs de pelle sur le gravier, bip de recul) ;
  - dès le passage 3, l'ambiance baisse et la musique revient.
- **Ce que dit le chef** (il faut garder ces mots exacts : ils correspondent à la transcription affichée dans l'application) :
  > « Rue des Lilas, tronçon 2. On a posé quarante mètres de PEHD diamètre 110 à un mètre vingt de profondeur. En fond de fouille, on est tombé sur un fourreau télécom qui n'est pas sur le plan, on l'a protégé. Remblaiement demain matin. »
- **Texte incrusté** (après la transcription) : « Il parle. Mire écrit, relève… et alerte. »
- **Voix off (narrateur, sur le passage 4)** : « Mire transcrit, relève le réseau, le diamètre, la profondeur… et repère l'anomalie : un fourreau télécom absent du plan. »

### Scène 5 : le bureau est prévenu (52-64 s)
- **Visuel** : fenêtre navigateur avec `captures/d01-conducteur-accueil-alertes.png`. Halo rouge sur le bloc « Alertes anomalies (2) ». Puis glissement vers `captures/d04-conducteur-note-vocale-synthese.png`.
- **Texte incrusté** : « Le conducteur est prévenu à l'instant. »
- **Voix off** : « Au bureau, le conducteur de travaux est prévenu au moment où c'est dit. Plus d'anomalie oubliée entre deux appels. »

### Scène 6 : tout le chantier au même endroit (64-74 s)
- **Visuel** :
  - `captures/d03-conducteur-fil-chronologique.png` : défilement lent du fil (photos, comptes-rendus, notes) ;
  - puis `captures/d05-conducteur-filtre.png`, avec un clic sur « Documents » ;
  - puis `captures/d06-conducteur-documents-echeances.png` ;
  - en insert, `elements/carte-dict-echeance.png` avec le badge orange « À échéance · expire dans 3 jours ».
- **Texte incrusté** : « DICT, récépissés, arrêtés : avec leurs échéances. »
- **Voix off** : « Photos, notes, comptes-rendus, DICT et récépissés : tout le chantier au même endroit, dans l'ordre, avec les échéances. »

### Scène 7 : le rapport client (74-84 s)
- **Visuel** : `captures/d07-conducteur-rapport-pdf-pret.png`, puis les pages du rapport (`captures/r01-rapport-pdf-page1.png`, `r02`, `r03`) qui se déploient en éventail.
- **Texte incrusté** : « Le rapport client en 1 clic. »
- **Voix off** : « En fin de semaine, le rapport PDF pour le client se génère en un clic. »

### Scène 8 : l'appel à l'action (84-92 s)
- **Visuel** : fond asphalte, logo négatif (`marque/mire-logo-horizontal-negatif.svg`) au centre. En dessous, `captures/s02-site-tarifs.png` en petit, flouté.
- **Texte incrusté** :
  - « Pour les équipes TP, VRD et réseaux » ;
  - **« Essai gratuit 14 jours, sans carte bancaire »** ;
  - **mirechantier.fr**, en jaune sur asphalte.
- **Voix off** : « Mire. Pour les équipes TP, VRD et réseaux. Essai gratuit de quatorze jours, sans carte bancaire, sur mirechantier.fr. »

---

## Format 2 : 9:16, environ 30 s (entièrement en vue POV)
1. Scène 1 (4 s) : texte centré, gros, sur le plan POV de la tranchée flouté.
2. Scène 3 (8 s) : POV, l'appareil photo s'ouvre, déclenchement, étiquette « Avant remblaiement ».
3. Scène 4 (13 s) : POV, le chef parle avec le bruit du chantier, la transcription s'écrit mot à mot, puis l'alerte rouge.
4. Scène 8 (5 s) : logo, « Essai gratuit », mirechantier.fr.

## Prises de vue POV et sons : d'où ils viennent
- **Si tu peux générer des plans vidéo réalistes** : génère les plans POV décrits dans les scènes 3 et 4 (tranchée VRD française, conduite PEHD bleue sur lit de sable, cônes, pelle mécanique, gants de travail, gilet orange visible en bas du cadre). Pas de visage, pas de logo de marque.
- **Sinon** : anime les illustrations de `elements/` (`vrd-tranchee-ouverte.jpg`, `vrd-avant-remblaiement.jpg`, `vrd-fourreau-telecom.jpg`). Fais un léger mouvement de caméra à l'épaule (parallaxe et petit tremblé), superpose une main tenant l'iPhone, et mets le viseur `elements/viseur-camera-iphone.png` sur l'écran.
- **Viseur de l'appareil photo** : `elements/viseur-camera-iphone.png` est un calque transparent au format de l'écran de l'iPhone (1179×2556). Le centre est vide : on y place l'image filmée.
- **Sons** : ambiance de chantier libre de droits (pelle mécanique, bip de recul, gravier), clic d'obturateur, voix du chef (texte exact plus haut), voix du narrateur.

Sous-titres incrustés en permanence : la majorité des gens regardent sans le son.

## Voix off
Voix masculine ou féminine française, posée, débit naturel, proche du terrain (pas « pub radio »). Si la voix n'est pas possible, garde les textes incrustés seuls : ils suffisent à comprendre la vidéo.

## Musique
Une musique instrumentale discrète et rythmée, à 10-15 % du volume sous la voix.

## À ne pas faire
- Inventer des écrans ou des fonctions qui ne sont pas dans les captures.
- Mettre du texte jaune sur fond clair.
- Afficher des prix (ils peuvent changer).
