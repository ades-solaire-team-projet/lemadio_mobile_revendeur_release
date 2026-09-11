"# lemadio_mobile_revendeur_release" 

Ce dépôt est réservé uniquement aux mises à jour **à distance** de l'application revendeur.

## Étapes de mise à jour

1. Apporter la modification ou ajouter la nouvelle fonctionnalité dans le code source.  
2. Incrémenter la version dans `pubspec.yaml`.  
3. Générer l’APK en mode release :  
   ```bash
   flutter build apk --release
4. Créer un nouveau release sur GitHub, dans ce dépôt.
5. Ajouter un tag (ex : v1.0.1) et un titre (ex : Version 1.0.1).
6. Uploader l’APK généré.
7. Publier le release en tant que latest.