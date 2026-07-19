# Organisation des photos — Les Trois Gourmets (projet Lovable « Gourmet Gatherings »)

Toutes les photos utilisées sont les vraies photos du restaurant, déjà téléversées
dans le projet Lovable (`src/assets`). Aucune image de banque d'images.

## Inventaire des photos disponibles

| Photo (asset) | Sujet |
|---|---|
| `hero-interior.jpg` | Salle et cave à vins (vue d'ensemble, soir) |
| `real-interior-wine.jpg` | Intérieur, mur de vins |
| `real-facade-1.jpg` | Façade du restaurant |
| `real-facade-terrasse.jpg` | Façade avec terrasse |
| `signature-dish.jpg` | Plat signature |
| `dish-tartare.jpg` | Tartare |
| `dish-dessert.jpg` | Dessert |
| `les-trois-gourmets-saint-jacques` | Saint-Jacques |
| `les-trois-gourmets-pates` | Pâtes |
| `les-trois-gourmets-oeufs` | Œufs |
| `les-trois-gourmets-soupe` | Soupe |
| `les-trois-gourmets-tartine` | Tartine |
| `les-trois-gourmets-cafe` | Café / mignardises |
| `les-trois-gourmets-10` à `16` (+ versions « enhanced ») | Ambiance, salle, détails |

## Affectation par page (règle : chaque photo à sa place logique, pas de doublon sur une même page)

| Page | Photos utilisées | Rôle de l'image |
|---|---|---|
| Accueil `/` | `hero-interior` (hero plein écran) | Immersion immédiate, donner envie en < 5 s |
| La Carte `/carte` | Plats : saint-jacques, tartare, pâtes, œufs, soupe, tartine, dessert, café | Donner faim, illustrer les menus dégustation |
| L'Expérience `/experience` | `real-interior-wine` + photos d'ambiance `les-trois-gourmets-1x` | Vendre l'atmosphère et le déroulé du dîner |
| Occasions `/occasions` | Photos d'ambiance intimiste (sélection `les-trois-gourmets-1x`) | Projeter le visiteur dans son occasion spéciale |
| Galerie `/galerie` | Toutes, en catégories filtrables | Preuve visuelle globale |
| Contact `/contact` | `real-facade-1` / `real-facade-terrasse` | Reconnaître le lieu à l'arrivée |

## Catégories de la galerie (filtres)

1. **Les plats** — saint-jacques, tartare, pâtes, œufs, soupe, tartine, dessert, café, plat signature
2. **La salle & la cave** — hero-interior, real-interior-wine, photos d'intérieur 10–16
3. **La façade & la terrasse** — real-facade-1, real-facade-terrasse

Grille élégante + lightbox au clic, CTA « Réserver » en fin de galerie.
