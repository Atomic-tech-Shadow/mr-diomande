# Link-In-Bio Portfolio - Mr Diomandé

## Overview
Un site link-in-bio professionnel et moderne pour showcaser tous les réseaux sociaux et profils de Mr Diomandé. Design épuré, animations fluides, **100% optimisé mobile**.

## Features Implémentées ✓
✅ **Profil Section** - Photo, nom, bio avec statistiques  
✅ **Icônes Réseaux** - 7 plateformes principales (Instagram, Twitter, LinkedIn, YouTube, TikTok, Discord, GitHub)  
✅ **Design Glassmorphism** - Effet de verre dépoli moderne  
✅ **Fond Animé** - Gradient dynamique + particules flottantes  
✅ **100% Mobile Responsive** - 4 breakpoints optimisés (768px, 600px, 480px, 360px)  
✅ **Touch-Friendly** - Boutons ≥60px, pas de tap highlight annoying  
✅ **Animations Fluides** - Hover effects et transitions smoothes  

## Responsive Design
- **Desktop (>768px)** - 75px boutons, espacing généreux
- **Tablet (600-768px)** - 68px boutons, padding optimisé
- **Mobile (480-600px)** - 64px boutons, layout compact
- **Small Mobile (<480px)** - 60px boutons, version ultra-compacte
- **Très Petit (<360px)** - Optimisé pour les anciens téléphones

## Technologies
- HTML5 sémantique
- CSS3 moderne (Glassmorphism, Backdrop Filter, Animations)
- Font Awesome 6.4 pour les icônes
- Google Fonts Poppins pour la typographie
- JavaScript vanilla pour les particules

## Structure Fichiers
```
.
├── index.html          # Page principale avec tout le CSS/JS
├── profil.jpg          # Photo de profil (140x140px)
├── i.jpg               # Ressource
├── goat.jpg            # Ressource
├── love.jpg            # Ressource
└── merci.png           # Ressource
```

## Déploiement
Utilise Python HTTP Server sur port 5000
```bash
python -m http.server 5000 --bind 0.0.0.0
```

## Personnalisation
Pour modifier les liens des réseaux sociaux, éditer le `href` dans les balises `<a>` :
- Instagram: `https://instagram.com/[username]`
- Twitter: `https://twitter.com/[username]`
- LinkedIn: `https://linkedin.com/in/[username]`
- YouTube: `https://youtube.com/@[channel]`
- TikTok: `https://tiktok.com/@[username]`
- Discord: `https://discord.gg/[code]`
- GitHub: `https://github.com/[username]`

## Recent Changes
- **Nov 30, 2025** - Création du projet avec design moderne
- Optimisation complète pour mobile (4 breakpoints)
- Implémentation du glassmorphism design trend
- Fond animé avec gradient dynamique et particules
- Intégration de toutes les images du ZIP
