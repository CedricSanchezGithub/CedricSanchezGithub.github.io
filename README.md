# CedricSanchezGithub.github.io

Site personnel servi par GitHub Pages depuis la branche `main`, racine du dépôt.
Chaque dossier devient un chemin : `ardoise/` est servi à
`https://cedricsanchezgithub.github.io/ardoise/`.

## Ce que ce dépôt contient

| Chemin | Contenu | Pourquoi c'est public |
|---|---|---|
| `/` | Accueil | Point d'entrée |
| `/ardoise/` | Politique de confidentialité d'Ardoise | Play Console exige une URL publique pour toute fiche d'application |

## Règles

**Du HTML statique, pas de générateur.** Un seul déploiement sert tout le site.
Sans build, une erreur dans une page ne peut pas empêcher les autres d'être
servies, et les URLs légales des applications restent en ligne quoi qu'il
arrive ailleurs.

**Les chemins des pages légales ne bougent pas.** Une URL de politique de
confidentialité est déposée dans Play Console et lue par les utilisateurs. Un
site refait ne doit pas casser `/ardoise/`.

**La source fait autorité ailleurs.** Le texte de la politique d'Ardoise est
maintenu dans le dépôt de l'application (`docs/confidentialite.md`) ; la page
ici en est la publication.
