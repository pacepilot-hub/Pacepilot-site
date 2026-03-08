# PacePilot Legal Site

## Français

Pages statiques publiques utilisées pour la conformité stores et le support utilisateur.

Ce dépôt (ou cette partie du projet) contient un mini-site pour :
- Une page vitrine produit
- Une URL de politique de confidentialité
- Une URL de support

### Pages

- `index.html` : page d'accueil PacePilot avec liens.
- `privacy.html` : politique de confidentialité pour App Store / Google Play.
- `support.html` : informations de support et contact.

### Pourquoi ce site existe

Les stores mobiles demandent des liens publics pour les informations légales et le support.
Ces pages statiques sont légères, rapides et faciles à maintenir.

### Aperçu local

Ouvre les fichiers directement dans un navigateur :
- `index.html`
- `privacy.html`
- `support.html`

Ou lance un serveur statique :

```bash
npx serve .
```

### Déploiement (GitHub Pages)

1. Pousse ces fichiers dans un dépôt public (recommandé : dépôt dédié `pacepilot-site`).
2. Dans GitHub : `Settings` -> `Pages`.
3. Choisis `Deploy from a branch`.
4. Sélectionne `main` et dossier `/ (root)`.
5. Sauvegarde puis attends la génération de l'URL GitHub Pages.

URLs attendues :
- `https://<username>.github.io/<repo>/`
- `https://<username>.github.io/<repo>/privacy.html`
- `https://<username>.github.io/<repo>/support.html`

### Checklist publication store

- Ajouter l'URL privacy dans App Store Connect et Google Play Console.
- Ajouter l'URL support dans App Store Connect et Google Play Console.
- Vérifier que l'email de support est valide et surveillé.
- Mettre à jour les textes en cas d'évolution du traitement de données.

### Sécurité

- Ne jamais mettre de clé API, secret ou code interne dans ce site public.
- Garder le code mobile et backend dans un dépôt privé.

### Contact

- Support : `support@pacepilot.app`

---

## English

Public static pages used for app-store compliance and user support.

This repository (or this project section) contains a minimal website for:
- A product landing page
- A privacy policy URL
- A support URL

### Pages

- `index.html`: PacePilot landing page with links.
- `privacy.html`: privacy policy for App Store / Google Play submission.
- `support.html`: support and contact details.

### Why this exists

Mobile stores require public legal and support links.
These static pages are lightweight, fast, and easy to maintain.

### Local preview

Open files directly in a browser:
- `index.html`
- `privacy.html`
- `support.html`

Or run any static server:

```bash
npx serve .
```

### Deploy (GitHub Pages)

1. Push these files to a public repository (recommended: dedicated `pacepilot-site`).
2. In GitHub: `Settings` -> `Pages`.
3. Choose `Deploy from a branch`.
4. Select branch `main` and folder `/ (root)`.
5. Save and wait for GitHub Pages URL generation.

Expected URLs:
- `https://<username>.github.io/<repo>/`
- `https://<username>.github.io/<repo>/privacy.html`
- `https://<username>.github.io/<repo>/support.html`

### Store submission checklist

- Add privacy URL in App Store Connect and Google Play Console.
- Add support URL in App Store Connect and Google Play Console.
- Ensure support email is valid and monitored.
- Update policy content whenever data handling changes.

### Security notes

- Do not place API keys, secrets, or internal code in this public site.
- Keep mobile app and backend source code in a private repository.

### Contact

- Support: `support@pacepilot.app`
