# PMM Market Partner — Pictarine

Expert marche factuel pour les squads Pictarine. Collecte, structure et confronte les donnees du marche photo US pour challenger le positionnement et le messaging des features.

## Ce que c'est

Un agent expert marche qui opere sur 4 niveaux :
1. **Opportunites / Marches** — sizing, tendances, segmentation, mouvements
2. **Positionnement / Value Prop** — mapping concurrentiel, espaces disponibles, confrontation
3. **Messaging** — collecte par canal, patterns, audit maquettes
4. **Validation GTM** — confrontation du plan GTM contre les donnees et le contexte

## Ce que ce n'est pas

Un PMM. L'agent ne prend pas de decision, n'interprete pas, ne recommande pas. Il se limite aux faits, sources et dates.

## Utilisation

1. Ouvrir une session Cowork avec le plugin installe
2. Dire ce qu'on cherche ou invoquer une commande (`/opportunities`, `/positioning`, `/messaging`, `/validate-gtm`)
3. Suivre le dialogue guide
4. L'agent produit une analyse sourcee dans Notion

Taper `/help-pmm` pour le guide complet.

## Commandes

| Commande | Description |
|---|---|
| `/opportunities` | Analyse marche (sizing, tendances, segmentation, mouvements) |
| `/positioning` | Mapping value props, espaces disponibles, confrontation |
| `/messaging` | Collecte messaging, patterns, audit maquettes |
| `/validate-gtm` | Confrontation du plan GTM |
| `/competitor [nom]` | Deep dive sur un concurrent |
| `/benchmark [feature]` | Benchmark comparatif sur une feature |
| `/audit` | Audit UX/wording d'une maquette |
| `/help-pmm` | Guide d'utilisation |

## Prerequis

- Notion (MCP) configure dans Cowork
- Web Search / Web Fetch disponibles
- Figma (MCP) pour les audits de maquettes
- Claude in Chrome pour le scraping
- Slack (MCP) pour le partage

## Installation

1. Cloner ce repo
2. Installer le fichier `.plugin` dans Cowork
3. Configurer les connexions Notion, Figma, Slack

## Structure

```
pmm-market-partner/
├── .claude-plugin/
│   ├── plugin.json
│   └── marketplace.json
├── skills/
│   ├── pmm-opportunities/SKILL.md
│   ├── pmm-positioning/SKILL.md
│   ├── pmm-messaging/SKILL.md
│   ├── pmm-validate-gtm/SKILL.md
│   └── references/
│       ├── bonnes-pratiques-pmm.md
│       ├── ecosystem-map.md
│       └── onboarding-guide.md
└── README.md
```
