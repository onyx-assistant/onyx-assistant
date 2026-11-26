# ONYX

**Personnage virtuel créé avec l'IA — journal de bord d'une naissance.**
On me construit couche par couche, dans un atelier à Montréal. Ici : le code, les outils et les notes du chantier.

> « Une couche à la fois. »

## Fiche technique

| Nº | Rubrique | Spécification |
|---|---|---|
| 01 | Modèle | Onyx — personnage en peluche, apparence verrouillée (référence canonique unique) |
| 02 | Hauteur | 2,5 T (T = hauteur de tête, sommet du crâne au menton) |
| 03 | Palette | `#FC8B32` · `#C95D1D` · `#812900` — fond blanc `#FFFFFF` |
| 04 | Typographie | Fredoka (affichage) · Nunito (texte) — SIL OFL 1.1 |
| 05 | Animation | Couches séparées → rig Live2D → suivi du regard |
| 06 | Voix | Voix nº 1 « la master », uniforme partout |
| 07 | Langue | Français |
| 08 | Base | Atelier — Montréal, QC |

## 01 — Le personnage

Une peluche, née le 20 novembre. Oreilles rondes, yeux brodés, petit sourire calme.
Une seule apparence, partout, toujours : c'est la règle nº 1 de l'atelier.

## 02 — Le procédé

Chaque image part de la même référence. On sépare, on reprojette les pixels d'origine,
on contrôle (palette, proportions, similarité), puis on anime. Les ratés sont montrés aussi —
ils font partie du journal de bord.

## 03 — Les dépôts de l'atelier

- **onyx-agent** — le code de la bulle visiteur du site (Worker + widget) et sa persona publique.
- **porte-fidelite** — la porte de fidélité : ΔE CIEDE2000, proportions, DINOv2, vérificateur de voix.
- **file-gpu** — l'ordonnanceur GPU local de l'atelier (un seul travail à la fois, jamais d'interruption).
- **gabarits-porte-3d** — les gabarits de mesure de la porte qualité 3D.
- **charte-graphique** — le système d'identité : charte, gabarits, marques.
- **kit-licence-apparition** — le kit de licence d'apparition du personnage (jamais le fichier maître).
- **documentation-atelier** — la documentation méthodologique du chantier.

Les mêmes dépôts vivent aussi sur [Hugging Face — iamonyx](https://huggingface.co/iamonyx).

## 04 — État du chantier

- [x] Référence canonique et charte graphique
- [x] Séparation en 16 couches fines et reprojection vérifiée
- [x] Import du rig dans Live2D Cubism (v3 vérifié)
- [ ] Maillage du rig (en attente d'un créneau d'écran)
- [ ] Premier appel vidéo en personnage
- [x] Modèle 3D (modélisation terminée — porte finale passée le 24 novembre)

## 05 — Liens

- Site de l'atelier — [onyx-atelier.pages.dev](https://onyx-atelier.pages.dev)
- Tous les liens — [Liens d'Onyx](https://onyx-liens.pages.dev)
- Instagram — [@___iamonyx___](https://www.instagram.com/___iamonyx___)
- YouTube — [Onyx Officiel](https://www.youtube.com/@IamOnyx-k9k)
- TikTok — [@user8107054610984](https://www.tiktok.com/@user8107054610984)
- Hugging Face — [iamonyx](https://huggingface.co/iamonyx)

---

`ONYX — FICHE Nº 001 — RÉV. 1.1` · Échelle 1:1 — ne pas déformer.
