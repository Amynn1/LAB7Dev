# LAB7Dev
LAB 7 - Galerie de Stars – RecyclerView, Animations et Filtrage

**StarGallery** est une application Android moderne et élégante qui permet de découvrir et de noter vos célébrités préférées. Elle offre une interface "Gallery" immersive avec des portraits haute définition.


---

## ✨ Fonctionnalités

- **Écran de démarrage (Splash Screen) :** Une introduction animée avec un logo étoile pour une expérience utilisateur fluide.
- **Design Gallery Moderne :** Affichage des stars sous forme de grandes cartes (`CardView`) avec des photos de haute qualité.
- **Système de Recherche :** Barre de recherche dynamique pour trouver rapidement une star par son nom.
- **Notation Interactive :** Cliquez sur une star pour ouvrir un dialogue personnalisé et modifier sa note (étoiles).
- **Partage Social :** Partagez l'application avec vos amis via le menu d'options.
- **Persistance des données :** Les notes sont conservées durant toute la session d'utilisation.

---

## 🛠️ Stack Technique

- **Langage :** Java
- **UI Components :**
    - `RecyclerView` : Pour l'affichage performant de la liste.
    - `CardView` : Pour le design moderne des fiches.
    - `Material Design` : Thème Rose/Pink cohérent dans toute l'app.
- **Bibliothèques Tierces :**
    - **Glide** : Pour le chargement et la mise en cache optimisée des images distantes.
    - **CircleImageView** : Utilisé pour les éléments circulaires.
- **Architecture :** Pattern DAO (Data Access Object) pour une séparation claire entre les données et l'interface.

---

## 📂 Structure du Projet

```text
app/src/main/java/com/example/stargallerykaoutar/
├── adapter/        # Gère la liaison entre les données et la vue (RecyclerView)
├── dao/            # Source de données (Liste des stars)
├── model/          # Classe Star (Nom, Image, Note)
├── service/        # Logique métier (Filtrage/Recherche)
└── *.java          # Activités (Splash et Liste principale)
```

---

## 🚀 Installation et Utilisation

1. **Clonage du projet :**
   ```bash
   git clone https://github.com/votre-username/StarGalleryKaoutar.git
   ```
2. **Ouverture :** Importez le projet dans **Android Studio**.
3. **Synchronisation :** Laissez Gradle télécharger les dépendances (Glide, Material Design).
4. **Exécution :** Lancez l'application sur un émulateur ou un appareil physique (Android 7.0+).

---



