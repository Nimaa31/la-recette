# Décrypte · site

Site de présentation de l’app iOS **Décrypte** : accueil, politique de confidentialité, conditions d’utilisation et aide, en français et en anglais (`/en`).

Le site est en HTML et CSS statiques, sans étape de build : Vercel le publie tel quel à chaque push.

Les pages sont générées depuis le projet de l’app (`scripts/build-landing.mjs`), à partir des mêmes textes que ceux affichés dans l’app. Pour modifier un texte, on le change dans l’app puis on régénère le site, plutôt que de retoucher ces fichiers à la main.

Polices : Bricolage Grotesque et Inter (licence SIL Open Font, voir `assets/fonts`).
