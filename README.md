🌟 Elle Entreprend - UJNK 2026
Site web d'inscription pour l'événement Elle Entreprend de l'Université Julius Nyerere à Kankan, Guinée.
✨ Caractéristiques
✅ 100% HTML/CSS/JavaScript - Aucune dépendance externe
✅ Responsive Design - Fonctionne sur tous les appareils (mobile, tablette, ordinateur)
✅ Stockage Local - Les données sont sauvegardées dans le navigateur (localStorage)
✅ Panel Admin Complet - Gestion des inscriptions en temps réel
✅ Design Moderne - Couleurs féminines, professionnelle, attrayante
✅ Prêt à Déployer - Copier-coller sur n'importe quel serveur
📁 Structure du Projet
```
elle_entreprend_html/
├── index.html          # Page d'inscription (formulaire)
├── admin.html          # Panel administrateur
└── README.md           # Ce fichier
```
🚀 Déploiement Rapide
Option 1: Netlify (Recommandé - Le Plus Simple)
Aller à: https://app.netlify.com
Cliquer "Add new site" → "Deploy manually"
Glisser-déposer le dossier `elle_entreprend_html`
✅ Votre site est EN LIGNE!
Avantages:
Gratuit
Domaine auto-généré
SSL inclus
Super facile
Option 2: Vercel
Aller à: https://vercel.com
Importer le projet
Deploy
✅ En ligne!
Option 3: GitHub Pages
Créer un repository GitHub
Uploader les fichiers
Settings → Pages → Deploy from branch
✅ En ligne!
Option 4: Serveur Web (Apache/Nginx)
Simplement copier les fichiers dans le dossier web de votre serveur:
Apache: `/var/www/html/`
Nginx: `/usr/share/nginx/html/`
📱 Pages du Site
Page d'Inscription (index.html)
Sections:
Hero (titre + appel à l'action)
Info cards (leadership, entrepreneuriat, networking)
Formulaire d'inscription complet
Footer avec contacts
Formulaire collecte:
Prénom, Nom
Email, Téléphone
Université
Catégorie (Étudiante, Diplômée, Porteuse de Projet)
Domaine d'intérêt
Description du projet
Intérêts (Leadership, Business, Pitch, Networking, Finance, Mentorat)
Panel Admin (admin.html)
Fonctionnalités:
📊 Stats en temps réel (Total, par catégorie)
🔍 Recherche par nom/email
👁️ Voir les détails de chaque inscription
🗑️ Supprimer des inscriptions
📥 Exporter les données en CSV
💾 Stockage des Données
Les données sont sauvegardées dans localStorage du navigateur:
Automatique après chaque inscription
Persiste même après fermeture du navigateur
Visible et modifiable dans l'admin
🎨 Design Responsive
Le site s'adapte parfaitement à:
📱 Téléphone (320px et plus)
📱 Tablette (768px et plus)
💻 Ordinateur (1200px et plus)
Testé sur:
Chrome, Firefox, Safari, Edge
iPhone, Android
Tablets, Desktops
🔧 Personnalisation
Changer les couleurs
Éditer le bloc `:root` dans le CSS:
```css
:root {
    --primary: #DB2777;        /* Rose principale */
    --secondary: #2F3C7E;      /* Bleu */
    --accent: #FFD700;         /* Or */
    /* ... */
}
```
Changer les textes
Éditer directement le HTML:
Titles
Descriptions
Contact info
Etc.
Ajouter des champs au formulaire
Ajouter dans le formulaire HTML:
```html
<div class="form-group">
    <label for="mon-champ">Mon Champ</label>
    <input type="text" id="mon-champ" name="monChamp">
</div>
```
Et ajouter dans le JavaScript:
```javascript
monChamp: formData.get('monChamp')
```
📞 Contact & Support
Email: foturemindinstitute@gmail.com
Téléphone: +224 620 770 934
📅 Détails de l'Événement
Dates: 28-29 Mars 2026
Lieu: Campus UJNK, Kankan, Guinée
Public: 50-100 femmes (étudiantes, diplômées, entrepreneures)
Inscription: GRATUITE et sans engagement
📜 Licence
Libre d'utilisation pour le projet Elle Entreprend - UJNK 2026.
---
Créé avec ❤️ pour l'autonomisation des femmes entrepreneures en Guinée
