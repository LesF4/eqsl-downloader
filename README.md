eQSL Downloader DXCC
Téléchargement, organisation et exploitation automatique des eQSL pour radioamateurs
> 📻 Version 2.3 FINAL — Décembre 2025
> Développé par **F4LPS** dans l'esprit *HAM SPIRIT*
---
⚠️ Note importante
Ce dépôt distribue un exécutable Windows pré-compilé. Le code source n'est pas publié à ce stade.
L'application demande votre identifiant et mot de passe eQSL.cc pour télécharger vos cartes. Comme pour toute application qui manipule des identifiants, ne lancez l'`.exe` que si vous faites confiance à l'auteur (F4LPS) et à la chaîne de distribution.
L'objectif de ce dépôt est de centraliser le téléchargement de l'application pour la communauté radioamateur francophone.
---
🎯 Fonctionnalités
📥 Téléchargement automatique des eQSL depuis eQSL.cc
🌍 Organisation par pays DXCC : 347 pays reconnus, 13 484 préfixes dans la base
🇫🇷 Sous-dossier dédié `France/TM/` pour les indicatifs TM (stations spéciales et événementielles)
🔄 Cache de reprise en cas d'interruption
🚫 Détection et évitement automatique des doublons
🎚️ Filtres disponibles : période, pays, INBOX / ARCHIVES, confirmées / non confirmées
---
📦 Installation
Rendez-vous dans la section Releases du dépôt
Téléchargez `eQSL_Downloader.exe` depuis la dernière version
Double-cliquez pour lancer (Windows uniquement)
> Aucune installation : il s'agit d'un exécutable autonome.
---
🚀 Utilisation
Lancez `eQSL_Downloader.exe`
Saisissez votre indicatif et votre mot de passe eQSL.cc
Choisissez le dossier de destination des QSL téléchargées
(Optionnel) Définissez vos filtres :
Date de début / fin
Pays spécifique
INBOX / ARCHIVES
Confirmées / Non confirmées
Cliquez sur DÉMARRER LE TÉLÉCHARGEMENT
Exemple d'arborescence générée
```
Mes_QSL/
├── France/
│   ├── TM/
│   │   ├── TM5FRA_20240101_1200_20M_SSB.jpg
│   │   └── TM0HQ_20240215_0800_40M_CW.jpg
│   ├── F4LPS_20240301_1400_10M_FT8.jpg
│   └── F4GBY_20240320_1600_15M_PSK31.jpg
├── England/
├── Germany/
└── ...
```
---
📜 Historique des versions
Version 2.3 FINAL — Décembre 2025
✅ Base DXCC complète : 347 pays, 13 484 préfixes (vs ~200 / ~7 500 en V2.2)
✅ Sous-dossier `TM/` pour les indicatifs spéciaux français
✅ Algorithme de reconnaissance amélioré
✅ Base de données nettoyée et optimisée
✅ Tous les bugs connus de la V2.2 corrigés
✅ Compatible avec les données existantes de la V2.2
Migration depuis la V2.2
Aucune action requise :
Les anciens dossiers restent compatibles
Le cache existant est conservé
Pas de perte de données
Remplacez simplement l'ancien `.exe` par le nouveau. Les nouvelles QSL utiliseront la nouvelle organisation (TM dans `France/TM/`), les anciennes restent telles quelles.
---
📜 Licence
Logiciel gratuit développé dans l'esprit HAM SPIRIT :
✅ Utilisation libre
✅ Distribution autorisée
✅ Modification autorisée (merci de créditer l'auteur)
---
👤 Auteur
F4LPS — Développeur principal
📧 `developpement@lesf4.fr`
🙏 Remerciements
F4LCL pour les tests et suggestions
La communauté radioamateur française
Tous les utilisateurs du programme
---
🐛 Signaler un bug ou suggérer une amélioration
Deux options :
Ouvrir une Issue sur ce dépôt GitHub
Envoyer un mail à `developpement@lesf4.fr` en précisant :
Description du problème
Capture d'écran si possible
Message d'erreur (si affiché)
Suggestions bienvenues : nouvelles fonctionnalités, autres sous-dossiers (TO, F/P, etc.), améliorations d'interface.
---
🔗 Maintenance du dépôt
Ce dépôt est maintenu par F4MAJ pour le compte de la communauté Les F4, afin de centraliser les développements logiciels de la communauté radioamateur francophone.
Site associé : f4maj.fr
---
📻 Bon téléchargement et bon trafic !
73 de F4LPS
