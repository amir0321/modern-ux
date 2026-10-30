# Modern UX – SaaS Landing Page i React & Tailwind

Ett frontend-projekt där jag byggde en modern landningssida för en SaaS-produkt (`Navbar`, `Hero`, `Features`, `Pricing`, `Testimonials` och `Footer`) i React 19 och Tailwind CSS.

## Teknikstack

- **Ramverk:** React 19 + Vite
- **Styling:** Tailwind CSS (mörkt tema med fokus på kontrast och typografi)
- **Arkitektur:** Datadrivna komponenter (`src/data/` + `src/components/`)

## Mina tankar, val och vad jag lärde mig

Syftet med det här projektet var att träna på **komponentstruktur, visuell hierarki och responsiv design** utan att förlita mig på färdiga komponentbibliotek.

- **Separera data från presentation (`src/data/`):**
  Istället för att upprepa långa block av JSX för varje prisplan eller kundrecension valde jag att lägga innehållet som strukturerade JavaScript-objekt i `src/data/` och rendera dem med `.map()`. Det gör komponenterna korta, läsbara och lätta att uppdatera.
- **Mörkt tema (`bg-slate-950`) och läsbarhet:**
  Jag jobbade med tydliga kontraster, luftig spacing och fokus på Call-to-Action-knappar i `Hero`- och `Pricing`-sektionerna.
- **Responsivitet från mobil till desktop:**
  Övade på att bygga flexibla grids i Tailwind som staplas snyggt på små skärmar och växer till flerkolumnslayouter på desktop.

## Köra lokalt

```bash
git clone https://github.com/amir0321/modern-ux.git
cd modern-ux
npm install
npm run dev
```
