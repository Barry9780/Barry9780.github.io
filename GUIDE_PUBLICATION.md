# Publier le portfolio sur GitHub Pages

1. Connectez-vous à GitHub avec le compte `Barry9780`.
2. Créez un dépôt public nommé **Barry9780.github.io** (sans README initial).
3. Sur la page du dépôt, cliquez **uploading an existing file**.
4. Glissez **les fichiers à l’intérieur de ce dossier**, pas le dossier lui-même : `index.html`, `styles.css`, `script.js`, `config.js`, `.gitignore`, `README.md` et éventuellement ce guide.
5. Vérifiez que `index.html` est à la racine du dépôt. Cliquez **Commit changes**.
6. Allez dans **Settings → Pages → Build and deployment**. Sélectionnez **Deploy from a branch**, branche **main**, dossier **/(root)** puis **Save**.
7. Attendez quelques minutes et ouvrez `https://barry9780.github.io/`.
8. Vérifiez les cinq boutons « Voir le code GitHub ».

## Ajouter votre LinkedIn

`https://www.linkedin.com/feed/` n’est **pas** votre lien de profil. Dans LinkedIn : cliquez sur **Vous → Voir le profil**, puis copiez l’adresse commençant par `https://www.linkedin.com/in/`. Ouvrez `config.js` et remplacez la valeur vide de `linkedinUrl` par ce lien, entre guillemets. Sur GitHub, ouvrez `config.js`, cliquez sur le crayon **Edit**, modifiez la ligne et cliquez **Commit changes**. Le site se mettra à jour automatiquement.

## Contact

Le site inclut le courriel `barryloukouta50@gmail.com` et le téléphone `289-823-3134`. Comme le site est public, ces informations seront visibles par tout le monde.
