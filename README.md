# GaMa Service — Sito Web Statico (v2 — pulito)

## Cosa è cambiato rispetto alla versione precedente

### 🔥 Aggiunto
- **Hero homepage** con H1 "Concretizziamo progetti, creiamo futuro" + CTA + visual
- **Hero in 3 pagine** prima senza H1: servizi.html, chi-siamo.html, manutenzione.html
- **Pagina servizi popolata** con 6 cards (era praticamente vuota)
- **JSON-LD Service + BreadcrumbList** su 6 pagine servizio (rich snippet su Google)
- **sitemap.xml** + **robots.txt**
- **Fix og:image** che puntava a file inesistente

### 🧹 Rimosso
- 184 KB di CSS morto (3 generazioni di codice menu sovrapposte)
- File ridotti del ~25% mantenendo identico aspetto e funzionalità

## Pagine
- `index.html` — Home (hero + soluzioni + stats + CTA)
- `servizi.html` — Hub servizi con 6 cards
- `chi-siamo.html` — Valori + punti di forza
- `impianti-meccanici-e-termotecnici.html`
- `impianti-elettrici.html`
- `impianti-speciali.html`
- `edilizia.html`
- `facility-management.html`
- `manutenzione.html`

## SEO & sicurezza
- JSON-LD strutturato (LocalBusiness, Service, BreadcrumbList)
- Open Graph + Twitter Card su tutte
- CSP, X-Content-Type-Options, Referrer-Policy, Permissions-Policy
- Sitemap.xml + robots.txt pronti per Google Search Console

## Tipografia
- Display: Archivo · Body: Manrope · Mono: JetBrains Mono

## TODO consigliati
- Creare og-image.jpg dedicata (1200x630) — attualmente punta a img-08
- Convertire logo da GIF a SVG
- Form di contatto reale (non solo tel:)
- Estrazione CSS in `assets/styles.css` condiviso (refactor lungo, opzionale)
