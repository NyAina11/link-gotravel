# Page de Redirection (Prête pour Vercel)

Cette page présente 3 boutons de redirection avec un design moderne (style Linktree / dark mode / glassmorphism).

## 🚀 Comment déployer sur Vercel ?

### Méthode 1 : Via l'interface web Vercel (le plus simple)
1. Créez un dépôt GitHub et poussez ce dossier dedans (ou glissez-déposez le dossier si vous utilisez l'import de dossier Vercel).
2. Rendez-vous sur [vercel.com](https://vercel.com) et connectez-vous.
3. Cliquez sur **"Add New..."** > **"Project"**.
4. Sélectionnez votre dépôt et cliquez sur **Deploy**. Vercel détecte automatiquement le projet statique.

### Méthode 2 : Via la ligne de commande (Vercel CLI)
Ouvrez un terminal dans ce dossier et exécutez :
```bash
npx vercel
```
Suivez les quelques instructions à l'écran, votre site sera en ligne en quelques secondes !

---

## ✏️ Comment modifier les 3 liens ?

Ouvrez le fichier [`index.html`](index.html).

Repérez les balises `<a>` :
- **Pour changer l'adresse de destination** : modifiez la valeur de `href="..."` (ex: `href="https://mon-lien.com"`).
- **Pour changer le titre du bouton** : modifiez le texte dans `<span class="btn-title">...</span>`.
- **Pour changer la description** : modifiez le texte dans `<span class="btn-desc">...</span>`.
