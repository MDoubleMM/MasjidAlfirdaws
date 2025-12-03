# 🕌 Mosquée Al Firdaws - Centre Culturel Musulman de Terrebonne

Site web officiel bilingue (FR/EN) de la Mosquée Al Firdaws, dédié à la présentation du projet de construction et à la collecte de fonds pour la communauté musulmane de Terrebonne.

---

## 📋 Table des matières

- [Description du projet](#description-du-projet)
- [✨ Nouvelles fonctionnalités](#-nouvelles-fonctionnalités)
- [Fonctionnalités actuellement implémentées](#fonctionnalités-actuellement-implémentées)
- [URIs fonctionnels](#uris-fonctionnels)
- [Technologies utilisées](#technologies-utilisées)
- [Structure du projet](#structure-du-projet)
- [Palette de couleurs](#palette-de-couleurs)
- [Système bilingue](#système-bilingue)
- [Fonctionnalités non implémentées](#fonctionnalités-non-implémentées)
- [Prochaines étapes recommandées](#prochaines-étapes-recommandées)
- [Contact](#contact)

---

## 🎯 Description du projet

La **Mosquée Al Firdaws** est un projet communautaire visant à construire un centre culturel et religieux permanent pour la communauté musulmane de Terrebonne. Ce site web sert de plateforme principale pour :

- Informer la communauté sur l'avancement du projet (FR/EN)
- Faciliter les dons via plusieurs plateformes sécurisées (GoFundMe, Interac, PayPal)
- Afficher les horaires de prière en temps réel
- Présenter les objectifs et les valeurs du centre

**Organisme de bienfaisance enregistré** : `770133734 RR 0001`

---

## ✨ Nouvelles fonctionnalités

### 🌐 **Site bilingue FR/EN**
- ✅ **Toggle de langue** en haut à droite (🇫🇷 FR / 🇬🇧 EN)
- ✅ **Détection automatique** de la langue du navigateur
- ✅ **Sauvegarde de la préférence** dans localStorage
- ✅ **Traduction complète** de tout le contenu
- ✅ **System de traduction dynamique** avec `data-i18n`

### 🕌 **Nouveau logo sans fond blanc**
- ✅ Logo moderne avec fond transparent
- ✅ Appliqué sur toutes les pages (accueil + 5 pages légales)
- ✅ Animation de glow subtile sur le hero

### ⏰ **Widget horaires de prière intégré**
- ✅ Widget Moonode TV pleinement intégré
- ✅ Responsive et adapté à tous les écrans
- ✅ Visible dès l'ouverture du site
- ✅ Design cohérent avec le reste du site

### 💳 **Lien PayPal de donation**
- ✅ Bouton PayPal fonctionnel
- ✅ Lien direct : https://www.paypal.com/ncp/payment/6VX6XYSYEP4UG
- ✅ Icône PayPal officielle

### 🎨 **Design amélioré**
- ✅ Animations de particules flottantes sur le hero
- ✅ Animation de glow sur le logo
- ✅ Effet de vague lumineuse au survol des cartes de don
- ✅ Bordures colorées au survol (orange/bleu)
- ✅ Transformations 3D subtiles
- ✅ Ombres portées plus profondes
- ✅ Coins arrondis modernisés (16px)

---

## ✅ Fonctionnalités actuellement implémentées

### 1. **Page d'accueil (index.html) - Bilingue**
   - Section Hero avec nouveau logo et animations
   - Section Projet détaillant les objectifs et étapes franchies
   - Section Horaires de prière avec widget Moonode intégré
   - Section Dons avec GoFundMe, Interac et PayPal
   - Section Contact avec email
   - Footer complet avec liens légaux

### 2. **Système bilingue complet**
   - Toggle FR/EN en haut à droite
   - Détection automatique de la langue du navigateur
   - Sauvegarde de la préférence utilisateur
   - Fichier `translations.js` avec toutes les traductions
   - Système `LanguageManager` pour gestion dynamique

### 3. **Navigation sticky améliorée**
   - Menu de navigation fixe avec nouveau logo
   - Menu mobile responsive avec animation hamburger
   - Liens de navigation avec scroll smooth
   - Active link highlighting basé sur le scroll

### 4. **Effet Scroll Reveal**
   - Animations d'apparition progressive au scroll
   - Fade-in + slide-up sur chaque section
   - Utilisation de l'Intersection Observer API
   - Animations délayées pour les cartes (stagger effect)

### 5. **Design responsive premium**
   - Mobile-first approach
   - Breakpoints optimisés (768px, 480px)
   - Menu mobile avec toggle
   - Grilles adaptatives pour tous les écrans
   - Widget horaires responsive

### 6. **Pages légales avec nouveau logo**
   - ✅ Avertissement sur les dons (`avertissement-dons.html`)
   - ✅ Conditions générales d'utilisation (`conditions-utilisation.html`)
   - ✅ Politique de confidentialité (`politique-confidentialite.html`)
   - ✅ Politique de cookies (`politique-cookies.html`)
   - ✅ Reçus d'impôt pour les dons (`recus-impot.html`)

### 7. **Animations et interactions modernes**
   - Particules flottantes sur le hero
   - Logo avec effet de glow pulsé
   - Cartes avec bordures colorées au survol
   - Effet de vague lumineuse sur les cartes de don
   - Transformations 3D subtiles
   - Transitions fluides partout

### 8. **Bouton "Retour en haut"**
   - Apparaît après 500px de scroll
   - Animation smooth au clic
   - Style cohérent avec la palette

---

## 🔗 URIs fonctionnels

### Pages principales
- **Accueil** : `/` ou `/index.html`
- **Section Projet** : `/#projet`
- **Section Horaires** : `/#horaires` (widget intégré)
- **Section Dons** : `/#don`
- **Section Contact** : `/#contact`

### Pages légales
- **Avertissement sur les dons** : `/avertissement-dons.html`
- **Conditions d'utilisation** : `/conditions-utilisation.html`
- **Politique de confidentialité** : `/politique-confidentialite.html`
- **Politique de cookies** : `/politique-cookies.html`
- **Reçus d'impôt** : `/recus-impot.html`

### Liens externes (dons)
- **GoFundMe** : https://www.gofundme.com/f/projet-mosquee-terrebonne-mosque-project
- **PayPal** : https://www.paypal.com/ncp/payment/6VX6XYSYEP4UG
- **Email Interac** : alfirdawsmasjid@gmail.com
- **Contact** : alfirdawsmasjid@gmail.com

---

## 🛠 Technologies utilisées

### Frontend
- **HTML5** - Structure sémantique avec `data-i18n`
- **CSS3** - Styles modernes avec variables CSS et animations
- **JavaScript (Vanilla)** - Interactivité native
- **Intersection Observer API** - Animations au scroll
- **localStorage API** - Sauvegarde de préférence de langue

### Bibliothèques externes (CDN)
- **Google Fonts** : Lora (serif) et Roboto (sans-serif)
- **Font Awesome 6.4.0** : Icônes vectorielles

### Design
- Mobile-first responsive design
- Flexbox et CSS Grid
- Animations CSS avancées (keyframes, transforms)
- Scroll smooth natif
- Particules flottantes animées

---

## 📁 Structure du projet

```
mosquee-al-firdaws/
│
├── index.html                          # Page d'accueil principale (bilingue)
├── styles.css                          # Feuille de styles principale
├── main.js                             # Script JavaScript principal
├── translations.js                     # ⭐ Système de traduction FR/EN
│
├── avertissement-dons.html             # Page légale : Avertissement
├── conditions-utilisation.html         # Page légale : CGU
├── politique-confidentialite.html      # Page légale : Confidentialité
├── politique-cookies.html              # Page légale : Cookies
├── recus-impot.html                    # Page légale : Reçus fiscaux
│
└── README.md                           # Documentation du projet
```

---

## 🎨 Palette de couleurs

La palette est inspirée du logo de la Mosquée Al Firdaws :

| Couleur | Code HEX | Usage |
|---------|----------|-------|
| **Bleu principal** | `#0D3B66` | Titres, navigation, footer |
| **Bleu secondaire** | `#1A237E` | Dégradés, accents |
| **Orange accent** | `#FFA500` | CTA, boutons, liens importants |
| **Blanc** | `#FFFFFF` | Texte sur fonds colorés, cartes |
| **Gris clair** | `#D3D3D3` | Bordures, backgrounds secondaires |

### Couleurs supplémentaires
- Texte foncé : `#2C3E50`
- Texte gris : `#6C757D`
- Background clair : `#F8F9FA`

---

## 🌐 Système bilingue

### Fonctionnement

Le site utilise un système de traduction dynamique complet :

#### 1. **Fichier de traductions** (`translations.js`)
```javascript
const translations = {
    fr: { nav_home: "Accueil", ... },
    en: { nav_home: "Home", ... }
};
```

#### 2. **Classe LanguageManager**
- Détecte automatiquement la langue du navigateur
- Charge la préférence sauvegardée (localStorage)
- Applique les traductions dynamiquement
- Gère le toggle FR/EN

#### 3. **Attribut data-i18n**
```html
<h1 data-i18n="hero_title">Mosquée Al Firdaws</h1>
```

#### 4. **Toggle de langue**
- Position fixe en haut à droite
- Drapeaux 🇫🇷 et 🇬🇧
- Style actif pour la langue sélectionnée
- Sauvegarde automatique de la préférence

### Ajouter une traduction

1. Ouvrir `translations.js`
2. Ajouter la clé dans `fr` et `en`
3. Ajouter `data-i18n="votre_cle"` dans le HTML

---

## ❌ Fonctionnalités non implémentées

### À développer dans le futur :

1. **Formulaire de contact** 📧
   - Actuellement : Email simple (mailto:)
   - Futur : Formulaire avec validation et envoi sécurisé

2. **Galerie photos du projet** 📷
   - Photos du terrain
   - Rendus 3D du futur bâtiment
   - Photos des activités communautaires

3. **Blog / Actualités** 📰
   - Annonces importantes
   - Mises à jour du projet
   - Événements communautaires

4. **Espace donateurs** 👥
   - Tableau d'honneur des donateurs
   - Suivi de l'objectif de collecte (barre de progression)
   - Statistiques de collecte en temps réel

5. **Calendrier des événements** 📅
   - Cours d'arabe et de Coran
   - Conférences
   - Activités familiales

6. **Multilingue étendu** 🌍
   - Actuellement : Français et Anglais
   - Prévu : Arabe classique

7. **Analytiques** 📊
   - Intégration Google Analytics
   - Facebook Pixel
   - Suivi des conversions

---

## 🚀 Prochaines étapes recommandées

### Priorité haute 🔴
1. **Optimiser le SEO**
   - Ajouter meta tags Open Graph
   - Créer un sitemap.xml
   - Optimiser les images (compression, lazy loading)
   - Ajouter schema.org markup

2. **Ajouter Google Analytics**
   - Suivre les visites et conversions
   - Analyser le comportement utilisateur
   - Tracker les changements de langue

### Priorité moyenne 🟡
3. **Implémenter une barre de progression des dons**
   - Afficher l'objectif de 2M$ et le montant collecté
   - Mise à jour manuelle ou automatique
   - Animation de progression

4. **Créer une galerie photos**
   - Ajouter des photos du terrain et du projet
   - Lightbox responsive
   - Lazy loading

5. **Ajouter l'arabe comme 3e langue**
   - Étendre le système de traduction
   - Adapter le layout RTL
   - Ajouter le drapeau 🇸🇦

### Priorité basse 🟢
6. **Développer le blog/actualités**
   - CMS simple ou fichiers statiques JSON
   - Système de pagination
   
7. **Ajouter un formulaire de contact**
   - Avec validation côté client
   - Backend pour envoi d'emails (PHP/Node.js ou service tiers)

8. **Optimisations de performance**
   - Minification CSS/JS
   - Compression d'images
   - Service Worker pour PWA

---

## 📞 Contact

**Mosquée Al Firdaws - Centre Communautaire de Terrebonne**

- 📧 **Email** : alfirdawsmasjid@gmail.com
- 🏛 **Organisme de bienfaisance** : 770133734 RR 0001
- 📍 **Localisation** : Terrebonne, Québec, Canada

### Méthodes de don
- **GoFundMe** : [Projet Mosquée Terrebonne](https://www.gofundme.com/f/projet-mosquee-terrebonne-mosque-project)
- **Interac** : alfirdawsmasjid@gmail.com (aucun mot de passe requis)
- **PayPal** : [Faire un don](https://www.paypal.com/ncp/payment/6VX6XYSYEP4UG)

---

## 📝 Changelog

### Version 2.0 - 2025-05-09
- ✅ Ajout du système bilingue FR/EN avec détection automatique
- ✅ Intégration du widget horaires de prière Moonode
- ✅ Nouveau logo sans fond blanc appliqué partout
- ✅ Lien PayPal de donation intégré
- ✅ Design amélioré avec animations modernes
- ✅ Effets de particules et glow sur le hero
- ✅ Cartes avec bordures colorées au survol
- ✅ Effet de vague lumineuse sur les cartes de don

### Version 1.0 - 2025-05-09
- ✅ Création du site web one-page
- ✅ 6 sections principales (Hero, Projet, Horaires, Dons, Contact, Footer)
- ✅ 5 pages légales complètes
- ✅ Design responsive mobile-first
- ✅ Effet scroll reveal
- ✅ Navigation sticky avec menu mobile

---

## 📄 Licence et droits d'auteur

© 2025 Mosquée Al Firdaws - Centre Communautaire de Terrebonne. Tous droits réservés.

---

## 🤝 Contribution

Pour toute suggestion d'amélioration ou question technique, veuillez contacter : **alfirdawsmasjid@gmail.com**

---

## 🎯 Résumé des améliorations apportées

### ✅ Complété
1. **Système bilingue complet** avec détection automatique et toggle FR/EN
2. **Nouveau logo sans fond blanc** appliqué sur toutes les pages
3. **Widget horaires de prière** pleinement intégré et responsive
4. **Lien PayPal de donation** fonctionnel
5. **Design premium** avec animations modernes :
   - Particules flottantes
   - Logo avec effet glow
   - Cartes avec bordures colorées
   - Effet de vague lumineuse
   - Transformations 3D

### 📊 Statistiques du projet
- **10 fichiers** (1 index + 1 CSS + 2 JS + 5 légales + 1 README)
- **2 langues** (FR + EN)
- **80+ traductions** dans chaque langue
- **3 méthodes de don** (GoFundMe, Interac, PayPal)
- **100% responsive** (mobile, tablette, desktop)

---

**Qu'Allah accepte vos efforts et vous récompense. 🤲**

*Dernière mise à jour : 9 mai 2025 - Version 2.0*