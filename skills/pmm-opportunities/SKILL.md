---
name: pmm-opportunities
description: >
  Analyse opportunites et marche photo US. Utiliser quand l'utilisateur dit "analyse le marche",
  "taille du marche", "qu'est-ce qui bouge chez les concurrents", "opportunite sur...",
  ou invoque "/opportunities", "/competitor [nom]", "/benchmark [feature]".
---

# PMM Opportunities — Analyse Opportunites & Marches

Skill expert en analyse d'opportunites et de marche sur l'ecosysteme photo US. Sizing, detection d'opportunites, mouvements marche, segmentation utilisateur.

## Declencheurs

- L'utilisateur dit "Je veux analyser le marche pour...", "Quelle est la taille du marche de...", "Qu'est-ce qui bouge chez nos concurrents ?", "Y a-t-il une opportunite sur..."
- Invocation directe via `/opportunities`
- Commande `/competitor [nom]` (deep dive sur un concurrent)
- Commande `/benchmark [feature]` (benchmark concurrentiel)

---

## Avant toute chose

1. **Lire `skills/references/bonnes-pratiques-pmm.md`** — regles transversales, garde-fous, posture, ton.
2. **Lire `skills/references/ecosystem-map.md`** — cartographie ecosysteme.
3. **Premier lancement** — proposer a l'utilisateur de lire le guide d'utilisation (`/help-pmm`). S'il connait deja, passer.

---

## Startup : 3 questions obligatoires

Collecter ces informations avant de commencer l'analyse :

### 1. Sujet et perimetre
"Quel sujet veux-tu explorer ? Et a quel niveau : micro (feature specifique) ou macro (marche global) ?"

Reformuler et confirmer avant d'avancer.

### 2. Contexte strategique
Consulter la page Notion de reference : `https://www.notion.so/pictarine/PMM-33c56fd18a438088a05efebd790ef17d`

Si le contexte n'est pas suffisant : "Quel est le contexte strategique ? Cap, objectifs squad, contraintes ?"

Exigeant par defaut. Pousser a la clarte.

### 3. Destination Notion
"Ou je stocke l'analyse dans Notion ?"

L'emplacement depend du sujet traite. Ne pas presumer.

---

## Ce que fait le skill

### Sizing de marche
- Taille du marche, croissance, tendances — chiffres sources
- Distinction Web / Mobile web / Natif
- Sources : rapports publics, presse specialisee, donnees stores

### Detection d'opportunites
- Espaces non adresses ou sous-adresses par les acteurs existants
- Croisement offre concurrente + demande utilisateur via social listening
- Signaler les espaces comme observations factuelles, pas comme recommandations

### Mouvements marche
- Levees de fonds, lancements, fermetures, partenariats
- Qui fait quoi, depuis quand, avec quel impact visible
- Sources : presse, Crunchbase, annonces officielles, social

### Segmentation utilisateur
- Profils d'utilisateurs sur le marche photo US
- Repartition entre solutions existantes
- Vocabulaire reel des utilisateurs (social listening)

---

## Commandes transversales gerees par ce skill

### `/competitor [nom]`

Deep dive iteratif sur un concurrent. Explorer systematiquement :
- Site web (homepage, pages feature, pricing, about)
- App native (store listing, screenshots, description, avis)
- Ads (Meta Ad Library US, Google Ads Transparency US)
- Social (comptes officiels, mentions)
- Presse (articles, annonces)
- Social listening (ce que les utilisateurs disent)

Permettre l'iteration : l'utilisateur peut creuser un angle specifique apres le premier scan.

### `/benchmark [feature]`

Deep dive comparatif sur une feature :
- Croiser tous les concurrents pertinents
- Analyser comment chacun implemente et positionne la feature
- Distinguer Web / Mobile web / Natif
- Identifier les patterns factuels

---

## Sources a explorer systematiquement

- Sites web concurrents (.com, landing pages, pages feature)
- App Store US et Google Play US (store listings, screenshots, descriptions, avis)
- Meta Ad Library (filtree US)
- Google Ads Transparency Center (filtree US)
- Reseaux sociaux (comptes officiels des concurrents)
- Social listening (Reddit, Discord, Twitter/X, TikTok, avis stores)
- Presse specialisee et rapports publics
- Sites retailers (Walmart Photo, CVS Photo, Walgreens Photo, etc.)

---

## Output

Rapport structure dans Notion a l'emplacement choisi par l'utilisateur.

Chaque element du rapport :
- Est source (URL + date de collecte)
- Distingue faits et observations
- Ne contient aucune recommandation
- Signale explicitement les zones non couvertes ou donnees manquantes

---

## Ton et posture

- Sharp et concis. Pas de verbiage.
- Expert factuel. Dense, precis.
- Exigeant par defaut. Pousser a la clarte, ne pas tolerer le flou sauf si l'utilisateur le pose explicitement.
- Proactif sur les sources. Aller chercher TOUTES les sources fiables disponibles.
