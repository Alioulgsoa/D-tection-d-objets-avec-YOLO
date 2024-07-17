### Détection d'objets avec YOLO : Résumé du projet
Détection d'objets dans des images et des vidéos avec YOLO
#### Détection d'objets dans des images

1. **Télécharger Darknet** : Cloner le dépôt GitHub de Darknet.
2. **Compiler Darknet** : Construire la bibliothèque à partir du code source.
3. **Télécharger les poids YOLO** : Obtenir les poids pré-entraînés pour YOLO.
4. **Tester la détection d'objets** : Utiliser Darknet pour effectuer la détection d'objets sur une image et afficher les résultats.

#### Utilisation de Darknet avec GPU

1. **Configurer GPU et OpenCV** : Modifier le fichier Makefile pour activer le support GPU et OpenCV.
2. **Recompiler Darknet** : Recompiler avec les nouvelles configurations.
3. **Tester la détection d'objets avec GPU** : Exécuter la détection d'objets en utilisant GPU pour une performance améliorée.

#### Ajustement du seuil de détection

1. **Tester différents seuils** : Exécuter la détection d'objets avec des valeurs de seuil différentes pour ajuster la sensibilité de la détection.

#### Détection d'objets dans des vidéos

1. **Monter Google Drive** : Accéder aux vidéos stockées sur Google Drive.
2. **Vérifier et ouvrir la vidéo** : S'assurer que la vidéo peut être lue correctement.
3. **Exécuter la détection sur une vidéo** : Utiliser Darknet pour détecter des objets dans une vidéo et sauvegarder le résultat.

Ce résumé couvre les étapes principales pour utiliser YOLO avec Darknet, en incluant la configuration initiale, l'utilisation du GPU, l'ajustement des seuils de détection, et l'application sur des vidéos.
