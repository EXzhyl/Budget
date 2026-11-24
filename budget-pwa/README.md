# Mon budget

Application de suivi des revenus, dépenses, récurrents et projets. Elle s’installe sur le téléphone comme une vraie application (PWA) et fonctionne hors connexion.

## Contenu du dossier

- `index.html` : l’application
- `manifest.json` : informations d’installation (nom, icônes, couleurs)
- `sw.js` : fonctionnement hors connexion
- `icons/` : icônes (cercle coloré)

## Mettre en ligne avec GitHub Pages (gratuit)

1. Créez un compte sur github.com, puis un nouveau dépôt public (par exemple `budget`).
2. Cliquez sur **Add file > Upload files** et déposez **tout le contenu** du dossier (y compris le dossier `icons`). `index.html` doit se trouver à la racine du dépôt. Validez avec **Commit changes**.
3. Allez dans **Settings > Pages**. Sous **Branch**, choisissez `main` et le dossier `/ (root)`, puis **Save**.
4. Après une à deux minutes, votre adresse apparaît : `https://VOTRE-NOM.github.io/budget/`

## Installer sur Android

1. Ouvrez cette adresse dans **Chrome**.
2. Menu ⋮ puis **Installer l’application** (ou « Ajouter à l’écran d’accueil »).
3. L’icône du cercle coloré apparaît sur l’écran d’accueil et l’application s’ouvre en plein écran.

## Installer sur iPhone

Ouvrez l’adresse dans **Safari**, touchez Partager puis **Sur l’écran d’accueil**.

## Vos données

- Elles sont enregistrées **uniquement dans le navigateur de l’appareil** (stockage local). Elles ne se synchronisent pas entre appareils.
- Elles sont propres à l’adresse du site : si vous changez d’adresse, elles ne suivent pas.
- Faites une sauvegarde de temps en temps : **Réglages > Sauvegarde > Copier**, puis collez le texte dans une note. Pour restaurer, collez-le dans la même zone et touchez **Restaurer**.
- Les dépôts GitHub Pages gratuits sont publics : n’y mettez jamais vos données, seulement l’application.

## Mettre à jour l’application

Si vous modifiez `index.html`, changez aussi `VERSION` dans `sw.js` (par exemple `budget-v2`) pour que les téléphones récupèrent la nouvelle version.
