# Nasazení Reality Kalkulačka Pro 4.0

## 🚀 Rychlé nasazení na Vercel

### Krok 1: Příprava GitHub repository
1. Vytvořte nový repository na GitHub
2. Nahrajte všechny soubory z tohoto ZIP
3. Commitněte a pushněte změny

### Krok 2: Nasazení na Vercel
1. Jděte na [vercel.com](https://vercel.com)
2. Přihlaste se pomocí GitHub účtu
3. Klikněte na "New Project"
4. Vyberte váš repository "reality-kalkulacka-pro"
5. Klikněte "Deploy"

### Krok 3: Výsledek
- Aplikace bude dostupná na: `https://reality-kalkulacka-pro.vercel.app`
- Automatické nasazení při každém push do main branch
- SSL certifikát zdarma
- CDN po celém světě

## 🔧 Alternativní nasazení

### GitHub Pages
```bash
# V repository settings
Settings → Pages → Source: Deploy from a branch → main → / (root)
```
URL: `https://vase-jmeno.github.io/reality-kalkulacka-pro`

### Netlify
1. Drag & drop složku na [netlify.com](https://netlify.com)
2. Nebo připojte GitHub repository
URL: `https://reality-kalkulacka-pro.netlify.app`

## 📁 Struktura souborů

```
reality-kalkulacka-pro/
├── index.html          # Hlavní aplikace
├── vercel.json         # Konfigurace pro Vercel
├── package.json        # NPM metadata
├── README.md           # Dokumentace
├── DEPLOYMENT.md       # Návod na nasazení
└── .gitignore         # Git ignore pravidla
```

## ⚙️ Konfigurace

### vercel.json
- Nastavuje statické hostování
- Přesměrování všech cest na index.html
- Optimalizace pro SPA

### package.json
- Metadata projektu
- Skripty pro lokální vývoj
- Informace o licenci a autorovi

## 🔍 Testování

### Lokální testování
```bash
# Nainstalujte serve globálně
npm install -g serve

# Spusťte lokální server
serve .

# Nebo použijte npm script
npm start
```

Aplikace bude dostupná na: `http://localhost:3000`

## 🌐 Vlastní doména

### Na Vercel
1. V dashboard projektu → Settings → Domains
2. Přidejte svou doménu
3. Nastavte DNS záznamy podle instrukcí

### Příklad DNS nastavení
```
Type: CNAME
Name: www
Value: cname.vercel-dns.com
```

## 📊 Monitoring

- Vercel Analytics (zdarma)
- Vercel Speed Insights
- Error tracking v dashboard

## 🔒 Bezpečnost

- HTTPS automaticky
- Security headers
- DDoS ochrana
- Edge caching

## 💡 Tipy

1. **Rychlé nasazení**: Vercel je nejrychlejší způsob
2. **Zdarma**: GitHub Pages i Vercel mají free tier
3. **Vlastní doména**: Možná na všech platformách
4. **Automatické nasazení**: Git push = automatický deploy
5. **Backup**: Vždy mějte zálohu na GitHubu

---

**Potřebujete pomoc?** Kontaktujte MEVERIK SOLUTION