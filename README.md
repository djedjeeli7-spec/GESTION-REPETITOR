# Gestion Répétiteur Android

## Méthode recommandée pour ce PC
Pas besoin d'installer Android Studio.

Le dossier contient un workflow GitHub Actions qui compile automatiquement l'APK dans le cloud.

### Étapes
1. Créer un compte GitHub gratuit sur github.com.
2. Créer un nouveau dépôt (repository), par exemple `GestionRepetiteur`.
3. Importer tous les fichiers de ce projet dans le dépôt.
4. Aller dans l'onglet **Actions**.
5. Choisir **Build APK** puis **Run workflow**.
6. Une fois terminé, ouvrir l'exécution et télécharger l'artefact **GestionRepetiteur-debug-apk**.
7. Extraire le ZIP téléchargé : il contient `app-debug.apk`.
8. Envoyer l'APK sur le téléphone et l'installer.

Cette méthode utilise les serveurs GitHub pour la compilation : Android Studio n'est donc pas nécessaire sur le PC.
