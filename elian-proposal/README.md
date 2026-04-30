# ELIAN Solutions — Redesign Proposal 2026

Propunere de redesign pentru ELIAN Solutions, creat de **Optirank Solutions** (optirank.net).

## 🚀 Deploy pe GitHub Pages

### Pasul 1 — Creează repository nou
```bash
# Pe GitHub.com: New repository → numele ex: "elian-proposal" → Public → Create
```

### Pasul 2 — Urca fisierele
```bash
cd /calea/catre/acest/folder
git init
git add .
git commit -m "Initial: Elian redesign proposal"
git branch -M main
git remote add origin https://github.com/USERNAME/elian-proposal.git
git push -u origin main
```

### Pasul 3 — Activează GitHub Pages
1. Mergi la repository → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **/ (root)**
4. Click **Save**

### Pasul 4 — Link-ul tău
```
https://USERNAME.github.io/elian-proposal/
```

Gata în ~2 minute după push.

---

## 📁 Structura

```
elian-proposal/
├── index.html    ← Singurul fișier. Zero dependențe.
└── README.md
```

**Zero build step. Zero npm install. Zero configurare.**  
Funcționează direct în browser, oriunde.

---

## ✏️ Personalizare rapidă

Dacă vrei să schimbi ceva înainte de trimitere:

- **Statistici** (500+, 18+, 50+): caută `stat-num` în HTML
- **Mesajul hero**: caută `hero-sub` 
- **Culoarea accent**: schimbă `--accent: #3B6FF0` în `:root`
- **Fonturi**: înlocuiește Syne + DM Sans cu alt pair din Google Fonts

---

*Propunere realizată de Optirank Solutions — optirank.net*
