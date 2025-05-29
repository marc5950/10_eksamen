# Ashira Oure Boxing Club

Dette repository indeholder kildekoden til Ashira Oure Boxing Club website for Københavns Erhvervsakademi (KEA). Hjemmesiden er bygget med Astro og inkluderer information om Ashira Oure Boxing Club, deres events, tilbud og praktisk information.

## Funktioner

- Responsivt design til både mobil og desktop
- Dynamisk side til forskellige boksehold med filtrering mellem 1:1 og holdtræninger
- Integration med Supabase som backend for hold data
- Kontakt os side med en form
- Visuel og interaktiv præsentation af trænerne

## Teknologier

- [Astro](https://astro.build/) - Web framework
- [Supabase](https://supabase.com/) - Database og API
- Vanilla JavaScript
- CSS
- HTML

## Projektstruktur

- `src/components/` - Genbrugelige UI komponenter
- `src/layouts/` - Side layout
- `src/pages/` - Forskellige sider og routes
- `src/assets/` - Billeder og andre statiske filer
- `src/styles/` - CSS styles
- `src/fonte/` - Web fonte

## Installation og kørsel

1. Klon dette repository:

```bash
git clone [repository-url]
```

2. Installer afhængigheder:

```bash
npm install
```

3. Start udviklingsserveren:

```bash
npm run dev
```

4. Byg til produktion:

```bash
npm run build
```

## Features

### Database med boksehold

Hjemmesiden inkluderer en database med de forskellige boksehold man kan melde sig til. Dette opdateres dynamisk via et API.

### Filter effekt

Der burges et filter billede overalt på sitet med "pointer-events: none;" så man ikke kan interagere med det.

### Responsivt design

Hjemmesiden er fuldt responsiv og tilpasser sig forskellige skærmstørrelser, fra mobil til desktop.

## Credits

Udviklet af Gruppe 9 for Ashira Oure Boxing Club

Patrick, Toke, Dani & Marcus
