# PREPA FS2 — application de révision

Application indépendante, accessible depuis un navigateur sur téléphone ou ordinateur. Sans mot de passe, sans compte, sans Abacus ni API payante.

**Lien du site après activation de GitHub Pages :** https://alexzucarello.github.io/prepa-fs2/

## Fonctionnalités

- Catalogue pédagogique de 148 appellations provenant du catalogue public Identif' Game, avec 5 compléments non officiels clairement séparés.
- QCM d'identification avec 14 photographies candidates issues de pages Wikimedia Commons ; leur adéquation aux variantes du FS2 doit être vérifiée.
- Ajout et import de questions personnelles, révisions, progression et sauvegarde locale JSON.
- Interface française et adaptée au mobile.

**Limites :** il ne s'agit pas de la banque intégrale du FS2, ni de la banque originale de l'application Abacus. Les références publiques sont des supports pédagogiques et non une liste officielle d'examen. Les photos externes requièrent Internet. Les données de progression restent sur chaque navigateur : exporter régulièrement la sauvegarde.

**Attention :** GitHub Pages est public. Ne pas verser de documents militaires ou photographies dont la diffusion n'est pas autorisée.

## Publication

GitHub → **Settings → Pages → Build and deployment → Source: GitHub Actions**. Le workflow `.github/workflows/pages.yml` déploie automatiquement le contenu public de la branche `main` à chaque modification.

PREPA FS2 est un projet d'étude distinct, sans intégration JARVIS.
