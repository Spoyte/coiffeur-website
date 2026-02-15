# Site Web Salon de Coiffure

Un site web professionnel, moderne et facile à maintenir pour un salon de coiffure.

## 🚀 Déploiement Rapide

### Option 1 : GitHub Pages (Gratuit)
1. Créez un repo GitHub
2. Poussez ces fichiers
3. Activez GitHub Pages dans Settings
4. Votre site est en ligne !

### Option 2 : Netlify (Gratuit + Formulaire)
1. Créez un compte sur [netlify.com](https://netlify.com)
2. Glissez-déposez le dossier du site
3. Le site est déployé instantanément

### Option 3 : Vercel (Gratuit)
1. Créez un compte sur [vercel.com](https://vercel.com)
2. Importez depuis GitHub
3. Déploiement automatique

## 📝 Personnalisation

### 1. Informations du Salon

Éditez `index.html` et remplacez :

- **Nom du salon** : Remplacez `[Nom]` par le vrai nom
- **Adresse** : Ligne 280 et 338
- **Téléphone** : Ligne 271 et 331
- **Email** : Ligne 333
- **Horaires** : Ligne 335-337

### 2. Photos

Remplacez les placeholders par de vraies photos :

| Emplacement | Taille recommandée | Description |
|-------------|-------------------|-------------|
| Hero section | 800x600px | Intérieur du salon |
| Galerie (6 photos) | 800x600px | Avant/après coupes |
| Section "Notre Histoire" | 600x600px | Photo de l'équipe |

### 3. Google Maps

Remplacez le placeholder carte (ligne 347) par votre iframe Google Maps :

1. Allez sur [Google Maps](https://maps.google.com)
2. Trouvez votre salon
3. Cliquez "Partager" → "Intégrer une carte"
4. Copiez le code `<iframe>`
5. Remplacez dans `index.html`

### 4. Réservation en Ligne

Pour activer la réservation en ligne (ligne 292) :

**Option A - Doctolib :**
```html
<a href="https://www.doctolib.fr/votre-lien" class="btn btn-primary">Réserver en ligne</a>
```

**Option B - Planity :**
```html
<a href="https://www.planity.com/votre-salon" class="btn btn-primary">Réserver en ligne</a>
```

**Option C - Widget intégré :**
Suivez les instructions de votre service de réservation.

### 5. Tarifs

Modifiez les prix dans la section "Tarifs" (lignes 195-250) selon vos prestations.

## 🎨 Personnalisation Avancée

### Couleurs

Dans `css/style.css`, modifiez les variables CSS (lignes 6-12) :

```css
:root {
    --color-primary: #8B5CF6;    /* Violet actuel */
    --color-secondary: #F59E0B;  /* Orange */
    /* Changez ces couleurs selon votre charte */
}
```

### Polices

Le site utilise Google Fonts. Pour changer :

1. Allez sur [fonts.google.com](https://fonts.google.com)
2. Choisissez vos polices
3. Remplacez le lien dans `index.html` (ligne 9)
4. Modifiez `--font-heading` et `--font-body` dans le CSS

## 📱 Fonctionnalités

- ✅ Design responsive (mobile, tablette, desktop)
- ✅ Navigation fixe avec smooth scroll
- ✅ Animations au scroll
- ✅ Menu mobile hamburger
- ✅ Formulaire de contact (à ajouter si besoin)
- ✅ SEO optimisé (meta tags, structure sémantique)
- ✅ Performance optimisée (CSS/JS minifiés)

## 🔧 Maintenance

### Mettre à jour les photos

Remplacez simplement les fichiers dans le dossier `images/`.

### Modifier les textes

Éditez directement `index.html` — tous les textes sont en français et facilement identifiables.

### Ajouter une page

1. Créez un nouveau fichier HTML
2. Copiez la structure de `index.html`
3. Modifiez le contenu
4. Ajoutez un lien dans la navigation

## 📞 Support

Pour toute question sur la personnalisation, n'hésitez pas à demander !

---

**Note pour le coiffeur :** Ce site est conçu pour être maintenu facilement. Vous n'avez besoin que d'un éditeur de texte basique (comme Notepad sur Windows ou TextEdit sur Mac) pour modifier les informations. Pas besoin de connaissances techniques !
