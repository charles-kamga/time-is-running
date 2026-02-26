# Time Is Running

Une page web minimaliste qui visualise le temps restant dans l'année à travers une grille de points.

## 🎯 Concept

**Time Is Running** est un outil de visualisation du temps qui affiche les 365 jours de l'année sous forme de points :
- **Points blancs** : jours restants dans l'année
- **Points gris** : jours déjà écoulés

Le design est épuré et direct, créé pour servir de fond d'écran ou de page de rappel temporel.

## ✨ Fonctionnalités

- **Visualisation instantanée** : Grille de 20×18 points représentant l'année complète
- **Mise à jour automatique** : Calcul en temps réel des jours restants jusqu'au 31 décembre
- **Design minimaliste** : Interface noir et blanc optimisée pour la concentration
- **Responsive** : Adapté à tous les écrans, particulièrement optimisé pour mobile
- **Message motivant** : Phrase d'impact sur le temps qui passe

## 🚀 Utilisation

1. **Ouvrir le fichier** : Double-cliquez sur `index.html` dans votre navigateur
2. **Visualiser** : La grille s'affiche automatiquement avec les jours restants en blanc
3. **Utiliser comme fond d'écran** : Capturez d'écran ou utilisez la page directement

## 🛠️ Technique

- **Langage** : HTML5 pur avec JavaScript vanilla
- **Style** : CSS3 avec Grid Layout et Flexbox
- **Compatibilité** : Tous les navigateurs modernes
- **Performance** : Léger et instantané

## 📱 Optimisation Mobile

- Police système Apple pour une cohérence parfaite avec iOS
- Fond noir pour économie de batterie sur écrans OLED
- Interface tactile optimisée
- Pas de dépendances externes

## 🎨 Design

- **Philosophie** : Minimalisme radical pour maximum d'impact
- **Couleurs** : Noir (#000), blanc (#fff), gris (#333)
- **Typographie** : Police système sans-serif
- **Grille** : 20 colonnes × 18-19 lignes (365 points)

## 📊 Calcul

Le temps restant est calculé comme :
```
jours_restants = ⌊(31_décembre - aujourd'hui) / 86_400_000⌋
```

## 🔧 Personnalisation

Pour modifier :
- **Total de jours** : Changez `TOTAL_DAYS` dans le JavaScript
- **Date de fin** : Modifiez la variable `end`
- **Couleurs** : Ajustez les valeurs CSS dans les classes `.dot` et `.active`
- **Message** : Éditez le `textContent` final

## 📄 Licence

Projet personnel - utilisation libre et open source.

---

*"Le temps ne négocie pas."*
