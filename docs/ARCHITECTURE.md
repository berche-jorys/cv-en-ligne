# Architecture de la Page Jekyll

## ✅ Ce qui a été créé

### 1. **Configuration (_config.yml)**
- Configuration propre et bien structurée
- Métadonnées SEO
- Support des médias sociaux
- Plugins Jekyll essentiels

### 2. **Layouts personnalisés**
- `default.html` : Template de base avec header et footer
- `page.html` : Template pour les pages intérieures
- `home.html` : Template spécialisé pour la page d'accueil avec hero section

### 3. **Includes réutilisables**
- `header.html` : Navigation sticky avec logo
- `footer.html` : Pied de page avec liens sociaux

### 4. **Système de styles SCSS**
- `variables.scss` : Couleurs, espacements, typographie
- `base.scss` : Éléments de base (typo, liens, boutons)
- `layout.scss` : Layout, header, footer, composants
- `utilities.scss` : Classes utilitaires, animations, shadows
- `style.scss` : Point d'entrée CSS

### 5. **Pages principales**
- `index.md` : Page d'accueil avec hero section
- `competences.md` : Tableau des compétences techniques
- `projets.md` : Showcase des projets
- `about.md` : Page à propos (optionnelle)

### 6. **Documentation**
- `README.md` : Guide complet du projet
- `Gemfile` : Dépendances Ruby/Jekyll
- `.gitignore` : Fichiers à ignorer

---

## 🎨 Design Features

### Responsive Design
- Mobile-first approach
- Breakpoints: 576px, 768px, 992px
- Flexbox et CSS Grid

### Typographie
- Système hiérarchique de titres
- Ligne de base cohérente (1.6)
- Police système (système d'exploitation)

### Couleurs
- Couleur primaire : #2c3e50 (dark blue)
- Couleur secondaire : #3498db (sky blue)
- Accent : #e74c3c (red)
- Excellente accessibilité WCAG

### Composants
- Boutons (primary et outline)
- Badges
- Cartes avec hover effects
- Tableaux stylisés
- Listes améliorées
- Code blocks avec syntax highlight

---

## 📦 Dépendances

```ruby
jekyll ~> 4.3.0
minima ~> 2.5
jekyll-feed ~> 0.12
jekyll-seo-tag ~> 2.8
```

---

## 🚀 Prochaines étapes recommandées

1. **Personnaliser _config.yml**
   - Mettre à jour le titre, description, auteur
   - Ajouter les vrais liens GitHub/LinkedIn

2. **Mettre à jour le contenu**
   - Remplir les sections compétences et projets
   - Améliorer la page à propos

3. **Ajouter des couleurs personnalisées**
   - Modifier les variables SCSS selon vos préférences
   - Tester la cohérence visuelle

4. **Déployer**
   - Sur GitHub Pages
   - Ou autre plateforme (Netlify, Vercel...)

5. **Améliorations futures**
   - Ajouter un formulaire de contact
   - Intégrer un blog
   - Ajouter des images d'arrière-plan
   - Animations au scroll

---

## 🔧 Commandes utiles

```bash
# Installer les dépendances
bundle install

# Lancer le serveur local
bundle exec jekyll serve

# Build pour la production
bundle exec jekyll build

# Nettoyer les fichiers générés
bundle exec jekyll clean
```

---

## 📝 Notes

- Pas de dépendances externes (Bootstrap, Tailwind)
- CSS custom et léger (~3-4 KB minifiés)
- Parfait pour un portfolio minimaliste
- Facilement extensible et maintenable
