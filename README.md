# hifdh-site

Le site public de l'application **Hifdh** — apprendre et mémoriser le Coran.

- Page d'accueil : <https://radhwanmrs.github.io/hifdh-site/>
- Politique de confidentialité : <https://radhwanmrs.github.io/hifdh-site/privacy/>

Cette dernière URL est celle déclarée dans la fiche Google Play : elle doit
rester accessible tant que l'application est publiée.

## D'où vient ce contenu

Les fichiers de ce dépôt sont la copie de `docs/site/` dans le dépôt de
l'application. **Modifier ici seulement pour un correctif urgent** : sinon les
deux versions divergent. La source fait foi.

## Déploiement

GitHub Pages sert directement le contenu de `main`, sans étape de construction :
le site est en HTML et CSS statiques, et `.nojekyll` demande à Pages de ne rien
transformer. Pousser sur `main` suffit donc à mettre le site à jour.

Réglage à faire une seule fois, dans **Settings → Pages** :
*Source* → **Deploy from a branch**, branche `main`, dossier `/ (root)`.
