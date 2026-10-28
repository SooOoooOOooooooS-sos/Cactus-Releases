# Cactus — Téléchargements

Ce dépôt public contient les applications Cactus et les fichiers de mise à jour. Aucun compte GitHub n'est nécessaire pour télécharger les applications.

| Plateforme | Télécharger |
| --- | --- |
| Windows 64 bits | [Cactus 2.0.10 — installateur Windows](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases/download/v2.0.10/Cactus-2.0.10-Windows.exe) |
| macOS | [Cactus 2.0.10 — application Mac](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases/download/v2.0.10/Cactus-2.0.10-Mac.zip) |
| Android | [Cactus Android 2.0.10 — APK testé](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases/download/v2.0.10/Cactus-2.0.10-Android.apk) |

[Toutes les versions](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases)

## Installer

- **Windows** : télécharger le fichier EXE et l'ouvrir.
- **Mac** : télécharger et extraire le ZIP, puis déplacer Cactus.app dans Applications. L'application n'utilise pas de certificat Apple Developer ID ; si macOS la bloque, consulter Réglages Système → Confidentialité et sécurité.
- **Android** : suivre les étapes ci-dessous.

### Android : première installation et partage

Le lien Android du tableau peut être envoyé directement à un ami : l'application n'a pas besoin d'être déjà installée et aucun compte GitHub n'est nécessaire.

1. Ouvrir le lien sur le téléphone Android et télécharger `Cactus-2.0.10-Android.apk`.
2. Ouvrir le fichier depuis les téléchargements du navigateur ou l'application Fichiers.
3. Si Android le demande, autoriser ce navigateur ou cette application Fichiers à installer des applications provenant de cette source.
4. Appuyer sur **Installer**, puis **Ouvrir**. Le téléchargement seul n'installe pas l'application.
5. Dans Cactus, renseigner sa playlist M3U ou ses propres accès IPTV autorisés.

L'APK Android ne s'installe pas sur iPhone ou iPad. Les intitulés des autorisations peuvent varier selon le téléphone.

## Validation Android

L'APK lié ci-dessus a été testé sur émulateur Android 15 : installation, démarrage, connexion avec une playlist M3U de test et mouvement vidéo détecté, sans crash détecté. Signatures APK v2/v3 vérifiées.

SHA-256 : `c7ccbbb0a7b4fc5b603ee7e051e645be3a7927099165a990eff6443119cc4583`

L'audio, les sous-titres, un fournisseur IPTV réel et un téléphone physique n'ont pas été testés pour cet APK. L'APK signé exact proposé ici a passé le test du 28 octobre 2026 (exécution GitHub Actions 40644826683), à partir de la version du code `209a8e8c2e06f77bb9a56f342d1306ec15e973a7`. La clé de signature est identique à celle de l'ancien APK.

[Ancien APK testé, conservé pour retour en arrière](https://github.com/SooOoooOOooooooS-sos/Cactus-Releases/releases/download/android-v2.0.10/Cactus-Android.apk). Son empreinte est `bb7858722c3bc8ddfa5e37b2d753478bd579e5f3de4cd79e10af1dc34983e221`.

## Mises à jour et confidentialité

Les fichiers `latest.yml`, `latest-mac.yml` et `.blockmap` servent aux mises à jour Windows/Mac : les conserver avec leurs installateurs. Le code source reste dans le dépôt privé Cactus.

Cactus ne fournit aucun abonnement ni contenu IPTV. Utiliser ses propres accès autorisés. Ne jamais publier de clé de signature, de mot de passe ou d'identifiants IPTV.
