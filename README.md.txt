# 🛒 Nos Besoins - Application Web Familiale

**Nos Besoins** est une application web progressive permettant à un couple (Mari & Femme) de gérer facilement les besoins du foyer, le budget mensuel en dinars algériens (DZD) et la liste des courses en temps réel.

---

## ✨ Fonctionnalités Principales

- 👩‍💻 **Double Profil** : Mode Femme (thème Rose/Fuchsia) et Mode Mari (thème Bleu/Gris).
- 🔄 **Synchronisation en Temps Réel** : Grâce à Firebase Realtime Database, chaque nouvel ajout ou changement de statut se met à jour immédiatement sur les deux téléphones.
- 💰 **Saisie du Prix Réel lors de l'Achat** : Lors du clic sur `✓ Acheté`, une fenêtre pop-up permet de saisir la quantité réelle et le prix unitaire payé en DZD.
- 🔔 **Notifications Web Push** : Reçevez une notification quand l'autre partenaire ajoute un besoin.
- 📊 **Gestion du Budget** : Calcul automatique des estimations vs dépenses réelles.
- 💾 **Persistance Hybride** : Fonctionne aussi bien en local (`localStorage`) qu'en ligne (Firebase).

---

## 🚀 Déploiement sur GitHub Pages (Gratuit)

1. Créez un dépôt sur GitHub nommé `nos-besoins`.
2. Envoyez les fichiers `index.html` et `README.md` sur le dépôt.
3. Sur GitHub, allez dans **Settings > Pages**.
4. Sous **Build and deployment / Branch**, choisissez `main` (ou `master`) et le dossier `/ (root)`, puis cliquez sur **Save**.
5. Votre application sera accessible en quelques secondes sur :
   `https://<votre-nom-utilisateur>.github.io/nos-besoins/`

---

## 📱 Installation sur Smartphone

1. Ouvrez l'URL GitHub Pages sur **Google Chrome** (Android) ou **Safari** (iOS).
2. Cliquez sur le menu de votre navigateur (`⋮` sur Chrome ou `⎋` sur Safari).
3. Sélectionnez **Ajouter à l'écran d'accueil**.