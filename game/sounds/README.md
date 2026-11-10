# Sons du jeu

Trois fichiers, installés le 02/09/2026 (EPIC 29).

| Fichier | Rôle | Source | Durée |
|---|---|---|---|
| `spin.mp3` | machine à sous, joué **en boucle** pendant le spin | Mixkit `sfx/1932` — *Slot machine wheel* | 6,2 s |
| `win.mp3` | jingle de gain | Mixkit `sfx/1936` — *Magical coin win* | 2,7 s |
| `loss.mp3` | son de perte | Mixkit `sfx/2024` — *Losing piano* | 2,1 s |

⚠️ **Ils manquaient depuis l'EPIC 6.** Le jeu était muet en production et
journalisait deux 404 par partie — constaté par l'EPIC 24, corrigé ici. Ce
README les réclamait (« déposer ici trois fichiers »), personne ne l'avait fait.

## Licence

**Mixkit Sound Effects Free License** — https://mixkit.co/license/
Usage commercial gratuit, **jeux vidéo explicitement autorisés**, **aucune
attribution requise**.

Interdit : redistribuer un son **seul**, comme stock, dans un outil ou un
template, ou le déposer à une société de gestion de droits. Les servir comme
sons d'un jeu, y compris pour plusieurs annonceurs d'une même plateforme, est
l'usage normal que la licence couvre.

## Remplacement par un annonceur

Les chemins sont dans l'habillage (`branding.mechanic.sounds`), donc un projet
peut fournir les siens sans toucher à ces fichiers. Le son ne démarre qu'après
la première interaction — contrainte des navigateurs, déjà gérée par
`useGameSounds.ts`, qui échoue en silence si un fichier manque.
