# Plan de site — Restaurant gastronomique à Valenciennes

## Contexte

- **Type d'établissement** : restaurant gastronomique
- **Localisation** : Valenciennes (Hauts-de-France)
- **Audience cible** : amateurs de bonne cuisine cherchant une expérience gastronomique pour un dîner d'exception ou une occasion spéciale (anniversaires, demandes en mariage, dîners d'affaires, célébrations)
- **Objectif principal du site** : générer des **réservations**

Toute décision de structure, de contenu et de design découle de cet objectif : chaque page doit rapprocher le visiteur de la réservation, avec un bouton « Réserver » visible en permanence (header sticky + rappels contextuels).

---

## 1. Arborescence du site

```
Accueil (/)
├── La Carte (/carte)
│   ├── Menus dégustation
│   ├── Carte des vins
│   └── Menus PDF téléchargeables
├── Réserver (/reservation)          ← page de conversion centrale
├── L'Expérience (/experience)
│   ├── Le Chef & l'équipe
│   └── La salle & l'ambiance
├── Occasions spéciales (/occasions)
│   ├── Anniversaires & célébrations
│   ├── Demandes en mariage
│   └── Privatisation & groupes
├── Galerie (/galerie)
├── Infos pratiques & Contact (/contact)
│   ├── Accès & plan (Valenciennes)
│   └── Horaires
└── Pages secondaires
    ├── Bons cadeaux (/bons-cadeaux)
    ├── Actualités / Événements (/actualites)     [optionnel, SEO]
    ├── Mentions légales (/mentions-legales)
    └── Politique de confidentialité (/confidentialite)
```

**Navigation principale (header, max 6 entrées)** :
La Carte · L'Expérience · Occasions spéciales · Galerie · Contact · **[Réserver]** (bouton mis en avant, couleur contrastée)

**Footer** : coordonnées complètes, horaires, plan d'accès, liens réseaux sociaux (Instagram prioritaire), bons cadeaux, mentions légales, newsletter.

---

## 2. Détail des pages

### 2.1 Accueil `/`

**Rôle** : séduire en moins de 5 secondes et orienter vers la réservation.

**Contenu (dans l'ordre)** :
1. **Hero plein écran** : photo ou vidéo courte d'un plat signature / de la salle, nom du restaurant, tagline (ex. « Une table d'exception au cœur de Valenciennes »), CTA principal **« Réserver une table »** + CTA secondaire « Découvrir la carte ».
2. **Présentation courte** (3–4 phrases) : philosophie de la cuisine, le chef, l'ancrage régional (produits des Hauts-de-France).
3. **Aperçu des menus** : 2–3 menus dégustation avec prix, lien vers la carte complète.
4. **Bandeau « occasions spéciales »** : anniversaire, demande, dîner d'affaires → lien vers /occasions.
5. **Preuve sociale** : 2–3 avis clients (Google / TripAdvisor), distinctions éventuelles (Gault&Millau, Michelin, Maître Restaurateur).
6. **Bandeau pratique** : horaires, adresse, carte Google Maps intégrée, téléphone cliquable.
7. **CTA final** : « Réservez votre table » (widget ou lien vers /reservation).

**Objectif de conversion** : clic sur « Réserver » (macro) ; clic vers La Carte ou Occasions (micro).

---

### 2.2 La Carte `/carte`

**Rôle** : c'est la page la plus consultée d'un site de restaurant — elle doit donner faim et rassurer sur le niveau et les prix.

**Contenu** :
- Menus dégustation (ex. Menu en 4 temps, Menu signature en 7 temps) avec **prix affichés clairement** — indispensable pour la cible « occasion spéciale » qui budgète sa soirée.
- Description sensorielle des plats (produits, provenance, saison) plutôt qu'une simple liste.
- Accords mets & vins proposés (avec supplément indiqué).
- Carte des vins : présentation de la cave, gammes de prix.
- Mention des régimes : végétarien, allergies (« signalez-les lors de la réservation » → lien réservation).
- Photos de plats intercalées (haute qualité, pas de stock).
- Mention « La carte évolue au fil des saisons » + date de mise à jour.
- PDF téléchargeable (menus + carte des vins) pour partage.
- **CTA sticky ou en fin de page** : « Cette carte vous fait envie ? Réservez votre table ».

**Objectif de conversion** : clic « Réserver » depuis la carte (c'est le passage n°1 vers la réservation) ; micro : téléchargement du PDF.

---

### 2.3 Réserver `/reservation` — page de conversion centrale

**Rôle** : convertir sans friction. Tous les chemins du site mènent ici.

**Contenu** :
- **Widget de réservation intégré** (ex. Zenchef, TheFork Manager, Guestonline, SevenRooms) directement dans la page — pas de redirection externe si possible, chaque redirection fait perdre des conversions.
- Champs : date, heure, nombre de couverts, occasion (menu déroulant : anniversaire, demande, dîner d'affaires…), demandes particulières / allergies.
- **Alternative téléphonique bien visible** : numéro cliquable (`tel:`) — la clientèle gastronomique aime aussi appeler, surtout pour les occasions spéciales.
- Politique claire : empreinte bancaire éventuelle, délai d'annulation, dress code s'il existe, horaires des services.
- Rassurance : « Confirmation immédiate par e-mail et SMS ».
- FAQ courte : enfants, parking à Valenciennes, accessibilité PMR, privatisation.

**Objectif de conversion** : **réservation confirmée** (conversion macro du site entier). KPI : taux de complétion du widget, part des réservations en ligne vs téléphone.

---

### 2.4 L'Expérience `/experience`

**Rôle** : vendre l'expérience, pas seulement l'assiette — c'est ce qui justifie le prix et déclenche la réservation « occasion spéciale ».

**Contenu** :
- **Le Chef** : portrait, parcours (maisons, mentors), philosophie de cuisine, lien au terroir du Valenciennois / des Hauts-de-France.
- **L'équipe** : sommelier, chef pâtissier, directeur de salle — humaniser le service.
- **La salle** : ambiance, décoration, nombre de couverts, photos d'atmosphère (lumière du soir).
- **Le déroulé d'un dîner** : storytelling du parcours client (accueil, mise en bouche, rythme du menu dégustation) — répond à l'anxiété du « à quoi s'attendre » des primo-visiteurs d'un gastronomique.
- Producteurs et fournisseurs locaux (transparence, ancrage régional).
- Distinctions et presse.
- **CTA** : « Vivez l'expérience — Réserver ».

**Objectif de conversion** : clic « Réserver » ; micro : temps passé sur la page, scroll complet (signal d'engagement).

---

### 2.5 Occasions spéciales `/occasions`

**Rôle** : page stratégique pour votre cible exacte. Capter les recherches « restaurant anniversaire Valenciennes », « restaurant demande en mariage », « dîner d'affaires Valenciennes ».

**Contenu, par section** :
- **Anniversaires & célébrations** : attentions possibles (dessert personnalisé, champagne à l'arrivée, placement en salle).
- **Demandes en mariage** : discrétion, mise en scène possible, coordination avec l'équipe.
- **Dîners d'affaires** : table au calme, facilité de facturation, menus adaptés au déjeuner d'affaires si proposé.
- **Groupes & privatisation** : capacité, salon privé éventuel, menus groupes → **formulaire de demande de devis dédié** (nom, date, nombre de personnes, budget, message).
- **Bons cadeaux** : encart avec lien vers /bons-cadeaux.
- Témoignages liés à des occasions (« Il a organisé sa demande ici… »).
- **CTA** : « Réserver pour une occasion spéciale » (pré-remplit le champ occasion du widget si possible).

**Objectif de conversion** : réservation avec occasion renseignée ; envoi du formulaire privatisation/groupes (lead qualifié à forte valeur).

---

### 2.6 Galerie `/galerie`

**Rôle** : preuve visuelle du niveau — l'image vend un gastronomique plus que le texte.

**Contenu** :
- Photos professionnelles organisées : plats, salle, cave, équipe en action, détails (dressage, arts de la table).
- Éventuellement une courte vidéo (30–60 s) d'un service.
- Flux Instagram intégré ou lien fort vers le compte.
- **CTA en fin de galerie** : « Réservez votre table ».

**Objectif de conversion** : clic « Réserver » après immersion visuelle ; micro : clic vers Instagram (notoriété).

---

### 2.7 Infos pratiques & Contact `/contact`

**Rôle** : lever les derniers freins logistiques — crucial pour une clientèle qui vient parfois de Lille, Douai, Cambrai ou de Belgique pour l'occasion.

**Contenu** :
- Adresse complète + **Google Maps intégrée**.
- **Accès** : depuis l'A2/A23, gare de Valenciennes, tramway ; **stationnement** (parkings proches du centre-ville, voiturier éventuel).
- Horaires des services (midi/soir, jours de fermeture) — en données structurées aussi.
- Téléphone cliquable, e-mail, formulaire de contact simple (pour tout ce qui n'est pas une réservation).
- Accessibilité PMR.
- **Rappel clair** : « Pour réserver une table, utilisez notre module de réservation » → lien /reservation (éviter que des réservations arrivent par le formulaire de contact).

**Objectif de conversion** : redirection vers /reservation ou appel téléphonique ; micro : clic itinéraire Google Maps.

---

### 2.8 Bons cadeaux `/bons-cadeaux`

**Rôle** : revenu additionnel parfaitement aligné avec la cible « occasion spéciale » (offrir un dîner gastronomique est un cadeau classique).

**Contenu** :
- Formules : montant libre, menu dégustation pour deux, accord mets & vins inclus.
- **Achat en ligne** avec envoi immédiat par e-mail (e-carte imprimable) — indispensable pour les cadeaux de dernière minute.
- Validité, conditions d'utilisation.

**Objectif de conversion** : achat d'un bon cadeau (conversion secondaire monétisée, qui génère ensuite une réservation).

---

### 2.9 Actualités / Événements `/actualites` (optionnel)

**Rôle** : SEO local et fidélisation — nouveaux menus de saison, dîners accords mets-vins, menus de fêtes (Saint-Valentin, fêtes de fin d'année, fête des mères).

**Objectif de conversion** : réservations sur événements datés (forte urgence naturelle : places limitées).

---

## 3. Parcours de conversion types

1. **Recherche locale** → Google « restaurant gastronomique Valenciennes » → Accueil ou fiche Google → Carte → **Réservation**.
2. **Occasion spéciale** → Google « restaurant anniversaire Valenciennes » → /occasions → **Réservation avec occasion**.
3. **Recommandation / Instagram** → Galerie ou Accueil → Expérience → **Réservation**.
4. **Cadeau** → /bons-cadeaux → **achat** → réservation ultérieure par le bénéficiaire.

Règle d'or : **le bouton « Réserver » ne doit jamais être à plus d'un clic**, sur mobile comme sur desktop (bouton sticky sur mobile).

---

## 4. Recommandations transverses

### SEO local (déterminant pour un restaurant)
- Balises title/meta orientées « restaurant gastronomique Valenciennes », déclinées par page (« menu dégustation Valenciennes », « restaurant anniversaire Valenciennes »…).
- **Données structurées Schema.org `Restaurant`** : horaires, fourchette de prix, cuisine, avis, géolocalisation + `Menu` sur /carte.
- Fiche **Google Business Profile** parfaitement tenue (photos, menus, lien de réservation direct) — la majorité des réservations locales commencent là.
- Contenu textuel réel sur chaque page (pas de menus uniquement en PDF ou en image).

### Mobile d'abord
- \>70 % du trafic d'un site de restaurant est mobile : bouton « Réserver » sticky, numéro cliquable, menus lisibles sans zoom, temps de chargement < 3 s (photos optimisées).

### Contenu
- Photographie professionnelle obligatoire (c'est l'investissement n°1).
- Ton éditorial : élégant, sensoriel, sans jargon prétentieux.
- Site en **français**, avec version **anglaise** envisageable (proximité de la Belgique et clientèle d'affaires).

### Mesure
- Événements à tracker : clics « Réserver », réservations confirmées (callback du widget), appels (clics `tel:`), formulaire privatisation, achats bons cadeaux, téléchargements PDF.
- Objectif type : taux de conversion visite → réservation de 3–5 %.

---

## 5. Récapitulatif : pages et objectifs de conversion

| Page | Objectif de conversion principal | Objectif secondaire |
|---|---|---|
| Accueil | Clic « Réserver » | Navigation vers Carte / Occasions |
| La Carte | Clic « Réserver » (levier n°1) | Téléchargement PDF |
| **Réservation** | **Réservation confirmée** | Appel téléphonique |
| L'Expérience | Clic « Réserver » | Engagement (scroll, temps) |
| Occasions spéciales | Réservation « occasion » / lead privatisation | Lien bons cadeaux |
| Galerie | Clic « Réserver » | Clic Instagram |
| Contact | Redirection réservation / appel | Clic itinéraire |
| Bons cadeaux | Achat d'un bon | Inscription newsletter |
| Actualités | Réservation sur événement daté | Inscription newsletter |
