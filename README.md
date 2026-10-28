# Cactus — Téléchargements

Ce dépôt public contient les applications Cactus et les fichiers de mise à jour. Aucun compte GitHub n'est nécessaire pour télécharger les applications.

| Plateforme | Télécharger |
| --- | --- |
| Windows 64 bits | [Cactus 2.0.10 — installateur Windows](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases/download/v2.0.10/Cactus-2.0.10-Windows.exe) |
| macOS | [Cactus 2.0.10 — application Mac](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases/download/v2.0.10/Cactus-2.0.10-Mac.zip) |
| Android | [Cactus Android 2.0.11 — correctif réseau testé](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases/download/android-v2.0.11/Cactus-2.0.11-Android.apk) |

[Toutes les versions](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases)

## Installer

- **Windows** : télécharger le fichier EXE et l'ouvrir.
- **Mac** : télécharger et extraire le ZIP, puis déplacer Cactus.app dans Applications. L'application n'utilise pas de certificat Apple Developer ID ; si macOS la bloque, consulter Réglages Système → Confidentialité et sécurité.
- **Android** : suivre les étapes ci-dessous.

### Android : première installation et partage

Le lien Android du tableau peut être envoyé directement à un ami : l'application n'a pas besoin d'être déjà installée et aucun compte GitHub n'est nécessaire.

1. Ouvrir le lien sur le téléphone Android et télécharger `Cactus-2.0.11-Android.apk`.
2. Ouvrir le fichier depuis les téléchargements du navigateur ou l'application Fichiers.
3. Si Android le demande, autoriser ce navigateur ou cette application Fichiers à installer des applications provenant de cette source.
4. Appuyer sur **Installer**, puis **Ouvrir**. Le téléchargement seul n'installe pas l'application.
5. Dans Cactus, renseigner sa playlist M3U ou ses propres accès IPTV autorisés.

L'APK Android ne s'installe pas sur iPhone ou iPad. Les intitulés des autorisations peuvent varier selon le téléphone.

## Validation Android

Android 2.0.11 active le transport HTTP natif pour charger les playlists et API sans dépendre des autorisations CORS du serveur. L'APK signé exact a passé le test sur émulateur Android 15 avec une playlist servie sans en-tête CORS : installation, démarrage, connexion M3U, requête vidéo et mouvement à l'écran réussis, sans crash détecté. Les 25 tests automatisés et les signatures v2/v3 sont validés ; la clé de signature est conservée.

SHA-256 : `829f1cbc502d08ef2177a376ec09220f7c2490a983bd5139a2fc4a5230dd798d`

Ce test ne prouve pas que le fournisseur d'un utilisateur particulier fonctionne. Audio, sous-titres, EPG et appareil physique restent à vérifier.

[Android 2.0.10 conservé](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases/download/v2.0.10/Cactus-2.0.10-Android.apk). Android peut refuser un retour à une version interne inférieure.

## Mises à jour et confidentialité

Les fichiers `latest.yml`, `latest-mac.yml` et `.blockmap` servent aux mises à jour Windows/Mac : les conserver avec leurs installateurs. Le code source reste dans le dépôt privé Cactus.

Cactus ne fournit aucun abonnement ni contenu IPTV. Utiliser ses propres accès autorisés. Ne jamais publier de clé de signature, de mot de passe ou d'identifiants IPTV.
