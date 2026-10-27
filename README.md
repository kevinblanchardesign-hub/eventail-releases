<p align="center">
  <img src="assets/logo.svg" alt="Eventail" width="128">
</p>

<h1 align="center">Eventail</h1>

<p align="center">
  <b>Convertir, compresser et ranger vos fichiers en un geste, sans quitter le Finder.</b><br>
  Faites glisser un fichier en maintenant une touche : un éventail d’actions s’ouvre autour du pointeur.<br>
  Lâchez sur une case, c’est fait. Le résultat apparaît à côté de l’original. 100 % local.
</p>

<p align="center">
  <a href="https://github.com/kevinblanchardesign-hub/eventail-releases/releases/download/latest-build/Eventail.dmg"><img src="assets/download-button.svg" alt="Télécharger Eventail (.dmg pour Mac)" width="410"></a>
</p>

<p align="center">
  <a href="https://github.com/kevinblanchardesign-hub/eventail-releases/releases/download/latest-build/Eventail.dmg"><b>Télécharger pour macOS</b></a> ·
  <a href="#sur-windows-aperçu"><b>Windows (aperçu)</b></a> ·
  <a href="#installer-en-3-étapes">Installer</a> ·
  <a href="#utiliser-eventail">Utiliser</a> ·
  <a href="https://github.com/kevinblanchardesign-hub/eventail-releases/releases">Toutes les versions</a> ·
  <a href="LICENSE">Licence</a>
</p>

<br>

## Installer en 3 étapes

> Il faut **macOS 14 Sonoma ou plus récent** (menu  → **À propos de ce Mac** pour vérifier), sur un Mac Apple Silicon ou Intel. Aucun compte n’est nécessaire.

### 1. Télécharger

Cliquez sur le bouton bleu **Télécharger Eventail** ci-dessus. Le fichier `Eventail.dmg` arrive dans votre dossier **Téléchargements**.

### 2. Mettre Eventail dans Applications

Double-cliquez sur **Eventail.dmg** : une fenêtre s’ouvre. Faites glisser l’**éventail bleu** sur le dossier **Applications**, à droite.
Vous pouvez ensuite éjecter le disque « Eventail » (clic droit → **Éjecter**) et mettre le `.dmg` à la corbeille.

### 3. Ouvrir Eventail la première fois (« Ouvrir quand même »)

Eventail n’est pas encore vérifié par Apple (notarisation). macOS le bloque donc **une seule fois**, à la première ouverture. C’est normal, voici comment l’autoriser :

1. Ouvrez le dossier **Applications** et double-cliquez sur **Eventail**.
2. macOS affiche « Eventail n’a pas été ouvert » (ou « Apple n’a pas pu confirmer… »). Cliquez sur **Terminé**. *Surtout pas sur « Placer dans la corbeille ».*
3. Ouvrez le menu  → **Réglages Système** → **Confidentialité et sécurité**.
4. Descendez tout en bas, jusqu’à la partie **Sécurité**. Vous y voyez « Eventail a été bloqué… » avec un bouton **Ouvrir quand même** : cliquez dessus.
5. Confirmez avec le mot de passe de votre Mac (ou Touch ID), puis cliquez encore sur **Ouvrir quand même**.

C’est fini : les fois suivantes, Eventail s’ouvre normalement.

> **Le bouton « Ouvrir quand même » n’apparaît pas ?** Il ne s’affiche qu’après une tentative d’ouverture, pendant environ une heure. Refaites l’étape 1, puis revenez dans **Confidentialité et sécurité**.
>
> Depuis macOS 15, le clic droit → **Ouvrir** ne suffit plus : il faut passer par les Réglages Système comme ci-dessus.

## Utiliser Eventail

Eventail n’a **pas d’icône dans le Dock** : il vit dans la **barre des menus**, en haut à droite de l’écran (un petit éventail). À l’ouverture, un message « Eventail est ouvert dans la barre des menus » le confirme. La première fois, un guide de bienvenue vous présente le geste.

**Le geste** : dans le Finder, commencez à faire glisser un fichier, puis **pendant le glisser** appuyez sur une touche (un simple appui suffit : l’éventail reste ouvert tant que vous glissez). Un éventail d’actions s’ouvre autour du pointeur. Lâchez le fichier sur une case : c’est fait, le résultat apparaît à côté de l’original (l’original n’est jamais modifié).

| Touche pendant le glisser | Éventail | Exemples |
| --- | --- | --- |
| **⌃ Contrôle** | Convertir | PNG → JPG, PDF → Word, MOV → MP4 |
| **⌥ Option** | Outils | Compresser, annoter (flèches, texte, flou…), pivoter, modifier un PDF, créer un ZIP |
| **⌘ Commande** | Actions fichier | AirDrop, créer un PDF, copier le texte d’une image ou d’un PDF |
| **⇧ Maj** | Favoris | vos actions préférées (à choisir dans Réglages → Favoris) |

Les touches se changent dans **Réglages → Eventail** (cliquez sur l’éventail en haut à droite, puis **Réglages…**).

**Vous ne voyez pas l’éventail en haut à droite ?** Sur un MacBook avec encoche, ou avec beaucoup d’icônes, il peut être caché derrière l’encoche. Double-cliquez à nouveau sur Eventail dans Applications : le guide s’ouvre et vous donne accès aux réglages.

**Autorisation Accessibilité (recommandée)** : dans **Réglages → Général**, le bouton **Ouvrir les Réglages Système** vous mène au bon endroit. Elle permet à l’éventail de réagir instantanément quand vous changez de touche.

## Sur Windows (aperçu)

Une première version pour **Windows 10 et 11**, avec le même éventail. Dans l’Explorateur, commencez à faire glisser un fichier, puis **pendant le glisser** appuyez sur **Ctrl** (Convertir), **Alt** (Outils) ou **Maj** (Actions fichier).

1. Téléchargez **[Eventail-Setup.exe](https://github.com/kevinblanchardesign-hub/eventail-releases/releases/download/windows-preview/Eventail-Setup.exe)** et double-cliquez dessus.
2. Si Windows affiche « Windows a protégé votre ordinateur » : cliquez sur **Informations complémentaires**, puis **Exécuter quand même** (l’app n’a pas encore de certificat Microsoft).
3. Cliquez sur **Suivant** jusqu’au bout (pas besoin de mot de passe administrateur). Eventail attend ensuite dans la zone de notification, en bas à droite près de l’horloge.

Pour l’instant : conversions d’images (JPG, PNG, PDF, GIF, TIFF, BMP, ICO), compresser, pivoter, créer un ZIP, copier, déplacer, copier le chemin. Le reste arrive par étapes.

## Mises à jour

Quand une nouvelle version sort, Eventail l’annonce dans une petite fenêtre avec la liste des nouveautés et un bouton **Installer la mise à jour**. Vous pouvez aussi cliquer sur l’éventail en haut à droite → **Rechercher des mises à jour…**, ou retélécharger avec le bouton ci-dessus à tout moment.

## Confidentialité

Tout se passe sur votre Mac. Aucun fichier, aucune métadonnée, aucune statistique n’est envoyé sur Internet : pas de compte, pas de serveur, pas de télémétrie.
Seule exception : Eventail télécharge toutes les 6 heures environ la liste des versions pour vous prévenir d’une mise à jour (désactivable dans Réglages → Général).

## Licence

© 2026 Kevin Blanchard. Tous droits réservés. Eventail est un logiciel propriétaire, fourni « en l’état », sans garantie : voir [LICENSE](LICENSE).
Vous pouvez l’utiliser sur vos propres Mac ; vous ne pouvez pas le revendre ni le redistribuer sans autorisation écrite.

Ce dépôt ne contient que les versions téléchargeables d’Eventail.
