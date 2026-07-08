# JEBO Timmerwerken — Dashboard

Bestelling & planning dashboard voor JEBO Timmerwerken.

## Live bekijken

Na het instellen van GitHub Pages is het dashboard bereikbaar op:  
`https://[jouw-gebruikersnaam].github.io/jebo-dashboard/`

## Installatie

1. Download of clone deze repository
2. Open `index.html` in je browser — werkt direct, geen server nodig

## GitHub Pages instellen

1. Ga naar je repository op GitHub
2. Klik op **Settings** → **Pages**
3. Kies bij **Source** → **Deploy from a branch**
4. Kies branch: **main**, map: **/ (root)**
5. Klik **Save**
6. Na ~1 minuut is de site live

## Supabase koppeling

Vul in `index.html` bovenaan het script jouw gegevens in:

```javascript
const SUPABASE_URL = 'https://jouw-project.supabase.co';
const SUPABASE_KEY = 'jouw-anon-key';
const ADMIN_EMAIL  = 'admin@jebo.nl';
```

## Updates uploaden

Na een aanpassing:
1. Vervang `index.html` in de repository
2. GitHub Pages publiceert automatisch de nieuwe versie
