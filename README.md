# PREPA FS2 — révision en ligne (GitHub Pages)

**Site public :** https://alexzucarello.github.io/prepa-fs2/

Application indépendante (ni JARVIS, ni Abacus), conçue pour téléphone et ordinateur, sans API payante. Elle est hébergée dans le dépôt GitHub d'origine.

## Accès direct

- [Accueil et IDENTIF photographique](./index.html)
- [Tableau IDENTIF FS2 et catalogue complémentaire](./identif-fs2.html)
- [QCM général, VBL et PAD](./qcm.html)

## Banques et catalogues effectivement intégrés

| Module | Contenu |
|---|---|
| QCM général | 200 questions tirées de la banque déjà présente dans le dépôt. Les réponses incertaines ne doivent pas être notées comme corrigées. |
| QCM VBL | 111 questions déjà présentes dans le dépôt. |
| Cartes PAD | 126 cartes déjà présentes dans le dépôt. |
| IDENTIF photographique | 14 photographies de référence publiques (candidatures à vérifier selon la variante), issues de pages Wikimedia Commons. |
| Tableau FS2 | 125 appellations transcrites sur les **132** annoncées sur la photo fournie ; sept entrées supplémentaires de la colonne VBCI ne sont pas visibles. |
| Catalogue Identif’ Game | 147 appellations conservées dans le dépôt existant, plus cinq compléments séparés. Ce catalogue public n'est pas la grille officielle du FS2. |

Le fichier [catalogue-fs2.json](./catalogue-fs2.json) conserve les neuf catégories de la photo, les graphies telles que transcrites, les sept entrées manquantes et les points de contrôle. Les variantes ne sont pas automatiquement fusionnées. Des noms non lisibles ne sont jamais inventés.

Les 125 appellations ne disposent **pas chacune d'une photographie validée** ; le QCM visuel en ligne se limite aux 14 photos candidates clairement signalées. Les images externes ont besoin d'Internet. Les sources et licences restent consultables depuis le QCM.

## MMP — uniquement en local

Le mémento fourni porte le marquage **« DIFFUSION RESTREINTE »**. Son contenu et les 134 questions qui en sont issues **ne sont pas versés dans ce dépôt public, ni sur GitHub Pages**. Le QCM MMP hors ligne reste dans les fichiers privés remis dans la conversation ; il n'est pas disponible sur ce site. Ne l'ajoutez pas au dépôt sans autorisation formelle de diffusion et contrôle approprié du moyen de stockage.

## Confidentialité et limites

- Ce dépôt et GitHub Pages sont **publics** : aucun mot de passe. « noindex » ne protège pas l'accès.
- Vos scores/progrès sur ce site sont enregistrés dans le navigateur local (pas de synchronisation entre appareils). Exportez régulièrement votre sauvegarde quand le module le permet.
- Les documents militaires, images internes et QCM provenant de supports à diffusion restreinte ne doivent pas être mis en ligne ici.
- Le contenu public est pédagogique : il ne prétend pas reconstituer une banque originale cachée ou tous les supports de votre formation.

## Déploiement

Le workflow [pages.yml](./.github/workflows/pages.yml) publie **seulement les fichiers du site public** à chaque modification de `main`. Activer GitHub Pages dans **Settings → Pages → Build and deployment → Source: GitHub Actions** si nécessaire.

Projet d'études indépendant de JARVIS.
