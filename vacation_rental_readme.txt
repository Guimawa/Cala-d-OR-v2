# 🏖️ Site Location Vacances Multi-Maisons - Espagne

## 📋 Description du Projet

Site web complet, moderne et responsive pour la location de maisons de vacances en Espagne. Interface publique multilingue avec panneau d'administration avancé.

## 🚀 Démarrage Rapide

1. **Cloner le repository**
```bash
git clone https://github.com/[username]/vacation-rental-site.git
cd vacation-rental-site
```

2. **Ouvrir avec un serveur local**
```bash
# Option 1: Python
python -m http.server 8000

# Option 2: Node.js
npx serve .

# Option 3: PHP
php -S localhost:8000
```

3. **Accéder au site**
- Site public: `http://localhost:8000`
- Interface admin: `http://localhost:8000/admin.html`

## 🔐 Accès Administration

- **URL**: `/admin.html`
- **Email**: `admin@site.com`
- **Mot de passe**: `admin123`

## 🌐 Langues Supportées

- 🇫🇷 Français (défaut)
- 🇪🇸 Espagnol
- 🇬🇧 Anglais
- 🇩🇪 Allemand
- 🇪🇸 Catalan

## 📁 Structure du Projet

```
vacation-rental-site/
├── index.html                 # Site public
├── admin.html                 # Interface admin
├── assets/
│   ├── css/
│   │   └── custom.css        # Styles personnalisés
│   ├── js/
│   │   ├── app.js            # Script principal site public
│   │   ├── admin.js          # Script interface admin
│   │   ├── database.js       # Gestion données localStorage
│   │   ├── multilang.js      # Système multilingue
│   │   ├── calendar.js       # Calendrier disponibilités
│   │   ├── swikly.js         # Intégration Swikly
│   │   └── utils.js          # Utilitaires
│   ├── images/
│   │   ├── placeholder.jpg   # Image par défaut
│   │   └── logos/
│   └── data/
│       ├── houses.json       # Données maisons (exemple)
│       ├── config.json       # Configuration site
│       └── translations.json # Traductions
├── README.md                 # Ce fichier
├── DEPLOY.md                 # Guide déploiement
└── .gitignore               # Fichiers ignorés
```

## 🛠️ Technologies Utilisées

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **Styling**: Tailwind CSS (CDN)
- **Stockage**: localStorage + JSON
- **Authentification**: Hash MD5 côté client
- **Responsive**: Mobile-first design
- **Multilingue**: Système de traduction dynamique

## 🎯 Fonctionnalités Principales

### Site Public
- ✅ Page d'accueil avec diaporama
- ✅ Catalogue de maisons avec filtres
- ✅ Pages individuelles des maisons
- ✅ Calendrier de disponibilités
- ✅ Système multilingue complet
- ✅ Responsive design
- ✅ Intégration Swikly pour cautions

### Interface Admin
- ✅ Dashboard avec statistiques
- ✅ Gestion complète des maisons (CRUD)
- ✅ Upload et gestion d'images
- ✅ Personnalisation du site
- ✅ Configuration multilingue
- ✅ Sauvegarde/restauration données
- ✅ Système de logs

## 🔧 Configuration

### Paramètres Swikly
1. Accéder à l'interface admin
2. Aller dans "Configuration" → "Swikly"
3. Configurer API Key et paramètres

### Personnalisation
- **Couleurs**: Modifiables depuis l'admin
- **Logo**: Upload via interface admin
- **Contenus**: Éditeur WYSIWYG intégré

## 📱 Responsive Design

- **Mobile**: 320px-768px
- **Tablet**: 768px-1024px
- **Desktop**: 1024px+

## 🔒 Sécurité

- Authentification admin avec hash MD5
- Validation des données côté client
- Protection contre XSS basique
- Limitation des tentatives de connexion

## 🌍 Déploiement

### Hébergement Statique
Compatible avec:
- GitHub Pages
- Netlify
- Vercel
- Surge.sh
- FTP traditionnel

Voir `DEPLOY.md` pour les instructions détaillées.

## 🧪 Test

### Données d'exemple
Le site inclut 6 maisons d'exemple avec:
- Photos (via Unsplash)
- Descriptions multilingues
- Tarifs et disponibilités
- Équipements complets

### Fonctionnalités testées
- ✅ Navigation multilingue
- ✅ Formulaires de contact
- ✅ Calendrier interactif
- ✅ Interface admin complète
- ✅ Sauvegarde/restauration

## 🐛 Dépannage

### Problèmes courants
1. **Site ne se charge pas**: Vérifier serveur local
2. **Admin inaccessible**: Vérifier URL `/admin.html`
3. **Images manquantes**: Vérifier permissions dossier
4. **Traductions manquantes**: Vérifier `translations.json`

### Support
- Consulter la documentation dans `/docs`
- Vérifier les logs dans la console navigateur
- Tester avec données d'exemple

## 📄 Licence

MIT License - Voir fichier LICENSE pour détails.

## 🤝 Contribution

1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commit les changements (`git commit -m 'Add AmazingFeature'`)
4. Push la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📞 Contact

Pour questions ou support:
- Email: contact@vacationrentals.com
- Issues GitHub: [Créer un ticket](https://github.com/[username]/vacation-rental-site/issues)

---

**Développé avec ❤️ pour la location de vacances en Espagne**