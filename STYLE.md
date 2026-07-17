# Charte visuelle — Restaurant gastronomique à Valenciennes

Ambition : **luxe et confiance**.
Règle d'or pour y arriver sans designer : **la sobriété fait le luxe**. Peu de couleurs, peu de polices, beaucoup d'espace. Quand vous hésitez, enlevez plutôt qu'ajouter.

---

## 1. Ambiance générale

Pensez à la salle d'un grand restaurant le soir : lumière chaude et tamisée, nappes claires, bois sombre, un éclat doré (laiton, bougie). Le site reproduit cette atmosphère :

- **Fonds sombres et chauds** pour les sections d'émotion (hero, galerie, CTA final).
- **Fonds ivoire** pour les sections de lecture (menus, FAQ, confiance).
- L'alternance sombre / clair rythme la page et évite la monotonie.
- Beaucoup de vide autour des éléments : c'est l'espace qui dit « luxe », pas les ornements.
- Aucune décoration gratuite : pas d'icônes fantaisie, pas d'effets clinquants, pas d'animations voyantes. Un filet doré fin (1 px) sous un titre suffit comme ornement.

---

## 2. Palette de couleurs

### Palette primaire (90 % du site)

| Rôle | Couleur | Hex | Usage |
|---|---|---|---|
| Fond sombre | Noir cacao | `#1C1917` | Hero, galerie, CTA final, footer |
| Fond clair | Ivoire | `#F7F3EC` | Sections de lecture, fond par défaut |
| Accent | Or doux | `#C0975C` | Boutons, liens, filets, petits titres |
| Texte sur clair | Brun très foncé | `#2B2622` | Tout le texte courant sur ivoire |
| Texte sur sombre | Ivoire voilé | `#EDE7DC` | Tout le texte sur fond noir cacao |

### Palette secondaire (10 % — touches ponctuelles)

| Rôle | Couleur | Hex | Usage |
|---|---|---|---|
| Vert bouteille | Vert profond | `#33413A` | Encarts (bons cadeaux, occasions), tags |
| Taupe | Gris chaud | `#8A8071` | Textes secondaires, légendes, dates |
| Blanc pur | Blanc | `#FFFFFF` | Cartes posées sur fond ivoire |

### Règles simples

1. **Jamais de noir pur (`#000000`) ni de gris froid** : toutes les teintes sont chaudes, c'est ce qui rend le site accueillant malgré le sombre.
2. **L'or est une épice, pas un ingrédient** : boutons, liens et filets seulement. Jamais en fond de section, jamais en couleur de texte courant.
3. **Maximum 2 couleurs par section** (fond + accent). Le texte ne compte pas.
4. Contraste : sur ivoire, texte brun foncé ; sur noir cacao, texte ivoire voilé. Ne jamais mettre l'or en petit texte sur ivoire (illisible).

---

## 3. Typographie

Deux polices seulement, toutes deux **gratuites sur Google Fonts** :

| Usage | Police | Graisse | Pourquoi |
|---|---|---|---|
| Titres | **Cormorant Garamond** | 500 (Medium) et 600 (SemiBold) | Serif élégante et fine — l'esprit d'une carte de grande maison |
| Corps de texte | **Inter** | 400 (Regular) et 500 (Medium) | Sans-serif neutre et très lisible, ne vole pas la vedette |

```html
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600&family=Inter:wght@400;500&display=swap" rel="stylesheet">
```

### Échelle de tailles (desktop / mobile)

| Élément | Taille | Détails |
|---|---|---|
| Titre hero (H1) | 56 px / 36 px | Cormorant 500, interlignage 1.1 |
| Titre de section (H2) | 40 px / 28 px | Cormorant 500 |
| Sous-titre (H3) | 24 px / 20 px | Cormorant 600 |
| Petit titre (surtitre) | 13 px | Inter 500, MAJUSCULES, espacement des lettres 2 px, couleur or |
| Corps de texte | 17 px / 16 px | Inter 400, interlignage 1.65 |
| Texte secondaire | 14 px | Inter 400, couleur taupe |

### Règles simples

1. Les titres en Cormorant, tout le reste en Inter — **aucune exception, aucune 3e police**.
2. Jamais de gras lourd (700+) : le luxe est léger.
3. Le « surtitre » doré en majuscules espacées (ex. « NOTRE CARTE ») au-dessus de chaque H2 : c'est le petit détail qui fait immédiatement « grande maison ».
4. Largeur de lecture : jamais plus de **65 caractères par ligne** (~680 px).

---

## 4. Boutons

### Bouton principal (« Réserver ma table »)

```css
background: #C0975C;      /* or */
color: #1C1917;           /* texte sombre — pas blanc */
font: 500 15px "Inter";
letter-spacing: 1.5px;
text-transform: uppercase;
padding: 16px 36px;
border: none;
border-radius: 2px;       /* presque carré : le luxe n'est pas arrondi */
```
Survol : fond légèrement éclairci `#CFA76C`, transition douce 0.2 s. Rien d'autre — pas d'ombre portée, pas d'agrandissement.

### Bouton secondaire (« Découvrir la carte »)

```css
background: transparent;
color: couleur du texte de la section;   /* ivoire sur sombre, brun sur clair */
border: 1px solid #C0975C;
/* mêmes padding, casse et rayon que le principal */
```
Survol : fond or à 10 % d'opacité.

### Règles simples

1. **Un seul bouton doré par écran visible.** S'il y a deux actions, la seconde est en bouton bordé.
2. Le libellé du bouton principal est **identique partout** : « Réserver ma table ».
3. Coins presque carrés (2 px) partout : boutons, cartes, images. Les gros arrondis font « appli », pas « grande table ».

---

## 5. Espacement

Tout se mesure en multiples de 8 px. Trois règles suffisent :

| Contexte | Desktop | Mobile |
|---|---|---|
| Entre deux sections | 112 px | 64 px |
| Entre un titre et son contenu | 40 px | 24 px |
| Entre les éléments d'un groupe (cartes, avis…) | 24 px | 16 px |

- **Largeur maximale du contenu : 1140 px**, centré, avec 24 px de marge latérale minimum sur mobile.
- Dans le doute, **doublez l'espace** que vous alliez mettre. Un site serré paraît bon marché ; un site aéré paraît cher. C'est la règle la plus rentable de toute cette charte.

---

## 6. Direction d'image

Les photos font 80 % de l'impression de luxe. Mieux vaut 10 photos excellentes que 40 moyennes.

### Ce qu'on photographie

- **Les plats** : en gros plan, un seul plat par image, sur la vaisselle réelle du restaurant.
- **La salle** : le soir, éclairée comme pendant le service (jamais au flash, jamais à midi avec les néons).
- **Les gestes** : mains du chef qui dresse, service du vin, flambage — le mouvement humanise.
- **Les détails** : arts de la table, cave, matière (lin, bois, laiton).

### Le style

1. **Lumière naturelle ou chaude, jamais de flash direct.** Ambiance légèrement sombre, comme une bougie : c'est le style « dark & moody » des grandes tables.
2. **Fonds sobres et sombres** derrière les plats — le plat est la seule star.
3. **Deux angles seulement** : vue plongeante (à la verticale) ou à 45°. La cohérence des angles fait le professionnalisme.
4. **Même traitement pour toutes les photos** : tons chauds, contraste doux. Si vous retouchez, appliquez le même réglage partout.
5. **Zéro photo de banque d'images.** Un visiteur qui reconnaît une photo stock ne réserve pas. Budget à prévoir : une demi-journée avec un photographe culinaire local — c'est le meilleur investissement du site.
6. Format : servir en WebP/AVIF, max 1920 px de large, pour garder un chargement < 3 s.

---

## 7. Récapitulatif express (à épingler)

- 3 couleurs qui font le site : noir cacao `#1C1917`, ivoire `#F7F3EC`, or `#C0975C`.
- 2 polices : Cormorant Garamond (titres), Inter (texte).
- 1 bouton doré par écran, libellé unique : « Réserver ma table ».
- Coins à 2 px, jamais de gros arrondis, jamais d'ombres.
- Espaces généreux : 112 px entre sections, dans le doute on aère.
- Photos : chaudes, sombres, réelles — jamais de stock.
- Quand on hésite : **on enlève.**
