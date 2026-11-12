# Drift — releases

Ce dépôt ne contient que les installateurs Windows de **Drift** et le fichier `latest.json`
que l'app lit pour se mettre à jour toute seule. Le code source n'est pas ici.

## Installer

Télécharge `Drift_x.y.z_x64-setup.exe` dans la [dernière release](../../releases/latest) et lance-le.
Les versions suivantes s'installent ensuite depuis l'app (Réglages › Mises à jour).

Chaque installateur est signé : l'app refuse toute mise à jour dont la signature ne correspond pas.

## Composants tiers

- **libmpv** (lecteur vidéo), sous licence GPL-2.0-or-later.
  Code source : https://github.com/mpv-player/mpv — build Windows : https://github.com/shinchiro/mpv-winbuild-cmake
- **Google Sans Flex** (police), sous licence SIL Open Font License 1.1.
