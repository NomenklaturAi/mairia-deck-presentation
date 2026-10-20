# MairIA — Deck IA\PERO · 22 octobre 2026

**Événement :** IA\PERO × Tech a Drink — Technopole de l'Aube / French Tech Est.
**Statut :** FOUNDER APPROVED — CHARLINE PENDING — PUBLICATION HOLD.
**Branche :** `pitch-ia-pero-2026-10-22` (ne pas merger sur `main` sans instruction explicite du Founder).

## Livrables

| Livrable | Emplacement dans le dépôt |
|---|---|
| Présentation HTML (11 slides) | `index.html` + `media/` |
| PDF final (11 slides + page de renvoi vers les spots, 12 pages) | `MairIA-IA-PERO-2026-10-22-FINAL.pdf` |

Navigation : flèches / espace / clic, `F` plein écran, `S` un ou deux spots.

## Structure

La racine du dépôt garde la forme attendue par GitHub Pages (`index.html` + `media/`), pour que la présentation publique puisse être remplacée sans changer d'URL.

`media/` contient aussi des fichiers que ce deck n'affiche plus. Ils sont conservés parce que `semtac.html`, publié depuis `main`, les utilise.

Hors dépôt (dossier local, exclu de Git) :

- `FINAL/` : paquet autonome — `index.html`, `MairIA-IA-PERO-2026-10-22-FINAL.pdf`, `assets/`.
- `ARCHIVE/anciennes-versions/` : HTML intermédiaires, PDF antérieur, captures d'itération.

## Publication (en attente)

Proposition : merger `pitch-ia-pero-2026-10-22` dans `main`.

- **Effet :** `index.html`, le PDF, `media/motion-still-web.jpg` et ce README changent.
- **Sans effet :** `semtac.html` et les médias existants restent identiques.

À exécuter uniquement après le retour de Charline ou une instruction explicite du Founder.
