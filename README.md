# AutismeGuiden

En moderne, tilgængelig og neurodivergent-venlig digital platform om autisme på dansk.

## Om projektet

AutismeGuiden er en gratis, åben platform med information om autisme for autistiske personer, pårørende, lærere og fagfolk. Platformen er bygget med tilgængelighed i fokus og overholder WCAG 2.2 niveau AA.

## Teknisk stack

- **Framework:** [Astro](https://astro.build/) v6
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) v4
- **Sprog:** TypeScript (strict mode)
- **Fonte:** Inter + Atkinson Hyperlegible

## Sider

| Side             | URL                | Beskrivelse                                    |
| ---------------- | ------------------ | ---------------------------------------------- |
| Hjem             | `/`                | Forsiden med hero, mission og navigations­kort |
| Hvad er Autisme? | `/hvad-er-autisme` | Autismespektret, myter vs fakta, FAQ           |
| Tilgængelighed   | `/tilgaengelighed` | WCAG 2.2, neurodivergent design­principper     |
| Ressourcer       | `/ressourcer`      | Søgbart ressourcebibliotek med filtrering      |
| Uddannelse       | `/uddannelse`      | Vejledning til lærere og pædagoger             |
| Om mig           | `/om-os`           | Mission, værdier, kontaktformular              |

## Tilgængeligheds­funktioner

- 🌙 **Mørkt tema** — fuldt understøttet
- **A** **Justerbar skriftstørrelse** — normal / stor / ekstra stor
- ⚡ **Reduceret bevægelse** — slår alle animationer fra
- ⌨️ **Tastaturnavigation** — komplet med synlige fokusringe
- 🔗 **Spring-til-indhold** — skjult link øverst på siden
- 🏷️ **Semantisk HTML5** — korrekt brug af ARIA og landmarks
- 💾 **Præferencer huskes** — gemt lokalt i browseren

## Farvepalette

| Token      | Farve   | Hex       |
| ---------- | ------- | --------- |
| Primary    | Blå     | `#4F7CAC` |
| Secondary  | Grøn    | `#7FB069` |
| Background | Lys grå | `#F8FAFC` |
| Surface    | Hvid    | `#FFFFFF` |
| Text       | Mørk    | `#1E293B` |

## Kom i gang

```bash
# Installer afhængigheder
npm install

# Start udviklingsserver
npm run dev

# Byg til produktion
npm run build

# Forhåndsvis produktions-build
npm run preview
```

## Projektstruktur

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Navbar.astro
│   │   ├── Footer.astro
│   │   ├── AccessibilityToolbar.astro
│   │   ├── Hero.astro
│   │   ├── FeatureCard.astro
│   │   ├── ResourceCard.astro
│   │   ├── FAQAccordion.astro
│   │   ├── SearchBar.astro
│   │   ├── SectionHeader.astro
│   │   └── Button.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── hvad-er-autisme.astro
│   │   ├── tilgaengelighed.astro
│   │   ├── ressourcer.astro
│   │   ├── uddannelse.astro
│   │   ├── om-os.astro
│   │   └── 404.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Licens

Indhold udgivet under åben licens. Kode under MIT.
