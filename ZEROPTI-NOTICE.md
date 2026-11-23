# Zeropti OS — avis de modification / modification notice

**Zeropti OS** et **Zeropti Manager** sont des versions modifiées d'**AtlasOS** et d'**Atlas Manager**
(https://github.com/Atlas-OS/Atlas), distribuées sous la même licence : **GNU GPL version 3** (fichier `LICENSE`).

Zeropti OS is a modified version of AtlasOS. It is **not affiliated with, endorsed by or supported by the AtlasOS project**.
For help with Zeropti OS, use the Zeropti support (https://discord.gg/MzxwsmqER), not the AtlasOS channels.

## Droits d'auteur / Copyright

- AtlasOS, Atlas Manager : copyright (c) AtlasOS contributors (voir l'historique Git et les fichiers d'origine).
- Modifications Zeropti : copyright (c) Zeropti, 2026, sous GPLv3.
- Les licences des composants tiers restent celles indiquées dans `app/licenses/` et
  `playbook/Executables/AtlasModules/README.md`.

## Code source

Le code source complet et correspondant de chaque version publiée de Zeropti OS et de Zeropti Manager
est disponible dans ce dépôt : https://github.com/la-signature/zeropti-os
(une version publiée = une étiquette Git et une « Release » GitHub).

## Modifications apportées (22/11/2026, branche `zeropti-branding`)

Seuls l'apparence, les noms visibles et les liens ont changé. **Aucune optimisation d'AtlasOS n'a été modifiée**,
et la logique d'installation est inchangée.

- Images : fonds d'écran, écran de verrouillage, icône du paquet (`playbook.png`), icône du dossier
  (`atlas-folder.ico`), icône et symbole de l'application (`app/assets/brand`, `app/resources/atlas.ico`).
  Les éléments de marque AtlasOS ont été retirés (ils ne sont pas sous GPLv3 : « All rights reserved »).
- Noms visibles : « Zeropti OS » (paquet, thèmes, raccourci du bureau) et « Zeropti Manager » (application,
  titre de fenêtre, propriétés du fichier, textes dans les 15 langues). « Atlas Toolbox » et les mentions
  d'AtlasOS liées à eclean sont conservées, car elles désignent les produits de l'équipe AtlasOS.
- Liens : dépôt, versions, traductions et Discord → Zeropti ; documentation et site d'AtlasOS conservés comme crédits.
- Recherche de mises à jour : versions publiées de ce dépôt (au lieu d'Atlas-OS/Atlas).
- Rapports : « Envoyer un rapport » n'envoie plus rien au service de l'équipe AtlasOS (reports.atlasos.net) ;
  il ouvre le support Zeropti sur Discord. L'export local du ZIP de diagnostic est conservé.
- Programme : `AtlasManager.exe` renommé `ZeroptiManager.exe` (cible Cargo, propriétés du fichier, scripts ISO/USB,
  tests, publication). Versions publiées : `Zeropti-OS-vX.Y.Z.apbx`, `Zeropti-OS-vX.Y.Z.zip`, `ZeroptiManager.exe`
  (workflow `release.yml`, exécuté seulement dans ce dépôt).
- Les noms internes (dossiers `AtlasModules`, `AtlasDesktop`, `AtlasOS`, modules PowerShell, identifiants du paquet)
  sont volontairement conservés pour ne pas casser l'installation ni les mises à jour.

## Zeropti Toolbox (novembre 2026, version 0.6.1)

- Zeropti OS installe **Zeropti Toolbox** (https://github.com/la-signature/zeropti-toolbox, version modifiée
  d'AtlasOS Toolbox, GPLv3) au lieu d'Atlas Toolbox : `Toolbox-Package.ps1` télécharge `AtlasToolbox-Setup.exe`
  depuis ce dépôt (identifiants du dépôt et du propriétaire épinglés), et les textes disent « Zeropti Toolbox ».
- Version 0.6.1 (mise à jour possible depuis 0.6.0).
