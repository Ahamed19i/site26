# Ahamed19i — Portfolio Personnel

Portfolio professionnel de **Ahamed Hassani Mhoma**, étudiant en Master 1 Systèmes & Réseaux à l'AFI-Université de l'Entreprise (Dakar, Sénégal).

🌐 **Site live** : [ahamed19i.netlify.app](https://ahamed19i.netlify.app) *(à mettre à jour après déploiement)*

---

## 🚀 Sections du site

- **Accueil** — Introduction, slogan, boutons CV & projets
- **À propos** — Parcours académique, compétences, certifications
- **Projets** — Galerie filtrée avec descriptions et technologies
- **Recherches** — Rapports et documents téléchargeables
- **Blog** — Articles tech, tutoriels réseaux et cybersécurité
- **CV interactif** — CV en ligne consultable + téléchargement PDF
- **Contact** — Formulaire + liens sociaux

## 🛠️ Technologies

- HTML5, CSS3, JavaScript vanilla
- Google Fonts (Syne, JetBrains Mono, Space Mono)
- Zero dépendances — fonctionne sans framework

## 📁 Structure du projet

```
portfolio/
├── index.html                  # Page principale
├── assets/
│   ├── files/
│   │   └── cv_ahamed_hassani.pdf   # CV téléchargeable
│   └── img/
│       └── photo.jpg           # Ta photo (à ajouter)
├── netlify.toml                # Config Netlify
├── .gitignore
└── README.md
```

## 📸 Ajouter ta photo

Place ta photo dans `assets/img/photo.jpg` puis dans `index.html`, remplace :
```html
<div class="avatar-placeholder">👨🏾‍💻</div>
```
par :
```html
<img src="assets/img/photo.jpg" alt="Ahamed Hassani Mhoma">
```
Fais la même chose dans `.cv-avatar` plus bas.

## 🌍 Déploiement sur Netlify (gratuit)

### Option 1 — Drag & Drop (le plus simple)
1. Va sur [app.netlify.com](https://app.netlify.com)
2. Clique sur **"Add new site" → "Deploy manually"**
3. Glisse-dépose le dossier `portfolio/` entier
4. ✅ Ton site est en ligne instantanément !

### Option 2 — Via GitHub (recommandé pour les mises à jour)
1. **Push sur GitHub** :
```bash
git init
git add .
git commit -m "Initial portfolio deployment"
git branch -M main
git remote add origin https://github.com/TON_USERNAME/portfolio.git
git push -u origin main
```
2. Sur [app.netlify.com](https://app.netlify.com) → **"Add new site" → "Import from Git"**
3. Sélectionne ton repo GitHub
4. Build settings : laisse tout vide (site statique)
5. Clique **Deploy** ✅

Chaque `git push` mettra à jour ton site automatiquement !

### Personnaliser l'URL
Sur Netlify : **Site settings → Domain management → Custom domains**
→ Exemple : `ahamed19i.netlify.app` (gratuit)

## ✏️ Personnaliser le site

- **Changer les liens GitHub** : cherche `github.com/ahamed19i` et remplace
- **Ajouter LinkedIn** : cherche `linkedin.com` dans le code et ajoute ton URL
- **Ajouter des projets** : copie un bloc `.project-card` dans `index.html`
- **Ajouter des articles** : copie un bloc `.blog-card`

## 📞 Contact

- 📧 ahassanimhoma20@gmail.com
- 📍 Médina, Dakar — Sénégal
- 💻 github.com/ahamed19i

---

*© 2025 Ahamed Hassani Mhoma — Tous droits réservés*
