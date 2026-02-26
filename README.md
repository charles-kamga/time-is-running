# ⏳ Time Is Running

## 📌 Description

Time Is Running est un générateur de fond d'écran dynamique conçu pour iPhone.
Il transforme le temps qui passe en signal visuel permanent, afin de renforcer la conscience du temps et stimuler la productivité personnelle.

Le principe est simple :
- Chaque point représente un jour
- Chaque point qui disparaît représente du temps perdu

## 🎯 Objectif du projet

Ce projet vise à :
- **Rendre le temps visible et tangible**
- **Créer une pression psychologique douce mais constante**
- **Éviter les rappels intrusifs** (notifications, alarmes)
- **Exploiter un simple fond d'écran comme outil de discipline personnelle**

L'utilisateur est confronté, à chaque déverrouillage du téléphone, à la réalité du temps restant dans l'année.

## 🧠 Principe de fonctionnement

Le projet repose sur une page web statique (HTML / CSS / JavaScript), sans backend ni API.

### 1. Calcul du temps
- La date courante est récupérée depuis le téléphone
- L'heure est normalisée à minuit pour garantir un changement de jour précis
- Le nombre de jours restants jusqu'au 31 décembre est calculé dynamiquement

### 2. Représentation visuelle
- L'année est représentée par 365 points
- Les points blancs représentent les jours restants
- Les points gris représentent les jours écoulés
- Le rendu est minimaliste pour maximiser l'impact visuel

### 3. Mise à jour automatique
- Le calcul est effectué à chaque chargement de la page
- Une automatisation iOS peut être utilisée pour :
  - ouvrir la page
  - capturer l'écran
  - définir l'image comme fond d'écran

Le fond d'écran est ainsi mis à jour quotidiennement sans intervention manuelle.

## 📱 Utilisation prévue

Ce projet est particulièrement adapté pour :
- **iPhone** (via l'app Raccourcis)
- **Écrans OLED** (fond noir → économie de batterie)
- **Utilisateurs cherchant à :**
  - mieux gérer leur temps
  - rester focalisés sur leurs objectifs
  - visualiser la progression (ou la perte) du temps

## 🚀 Installation et utilisation

1. **Ouvrir la page** : Accédez à `index.html` dans votre navigateur
2. **Visualiser** : La grille s'affiche automatiquement avec les jours restants en blanc
3. **Automatisation iOS** : Utilisez l'app Raccourcis pour :
   - Ouvrir la page web
   - Capturer l'écran
   - Définir comme fond d'écran
   - Programmer l'exécution quotidienne

## 🛠️ Technologies utilisées

- **HTML5** — structure de la page
- **CSS3** — mise en page et design minimaliste
- **JavaScript (vanilla)** — calcul du temps et génération dynamique
- **Hébergement statique** via GitHub Pages

## 🔒 Choix techniques

- **Aucun framework** (simplicité, rapidité, fiabilité)
- **Aucun appel réseau**
- **Aucune donnée utilisateur collectée**
- **Dépend uniquement de l'heure locale du téléphone**

Ces choix garantissent :
- **Stabilité**
- **Confidentialité**
- **Compatibilité maximale**

## 🎨 Design

- **Philosophie** : Minimalisme radical pour maximum d'impact
- **Couleurs** : Noir (#000), blanc (#fff), gris (#333)
- **Typographie** : Police système sans-serif
- **Grille** : 20 colonnes × 18-19 lignes (365 points)
- **Message** : "Le temps ne négocie pas."

## 📊 Calcul

Le temps restant est calculé comme :
```
jours_restants = ⌊(31_décembre - aujourd'hui) / 86_400_000⌋
```

## 🧩 Personnalisation possible

Le code peut facilement être adapté pour :
- **Date cible personnalisée** (examen, projet, objectif)
- **Message psychologique différent**
- **Nombre de points différent**
- **Thème visuel différent**
- **Usage sur desktop ou tablette**

## ⚠️ Limites connues

- iOS impose parfois une confirmation lors du changement de fond d'écran
- L'année est fixée à 365 jours (les années bissextiles ne sont pas prises en compte par choix de simplicité)

## 📄 Licence

Projet personnel, libre d'utilisation et de modification à des fins éducatives ou personnelles.

## ✍️ Auteur

Conçu comme un outil de discipline personnelle, et non comme un produit commercial.

---

*"Le temps ne négocie pas."*
