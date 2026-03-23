# Ankit Singh — Portfolio (React + Three.js)

A fully responsive, animated portfolio built with **React 19**, **Three.js 3D background**, and a **Light/Dark theme toggle**.

## 🚀 Quick Start

### 1. Install dependencies

```bash
npm install
```

### 2. Run dev server

```bash
npm run dev
```

Open http://localhost:5173

### 3. Build for production

```bash
npm run build
```

Then deploy the `dist/` folder to **Netlify**, **Vercel**, or **GitHub Pages**.

---

## 📁 File Structure

```
ashu-portfolio/
├── index.html              ← HTML entry
├── vite.config.js          ← Vite config
├── package.json            ← Dependencies
├── AnkitPortfolio.jsx       ← ✅ MAIN FILE — edit everything here
└── src/
    └── main.jsx            ← React root mount
```

## ✏️ How to Edit

**Everything editable lives at the top of `AnkitPortfolio.jsx`** in the `DATA` object:

| What to change            | Where                                  |
| ------------------------- | -------------------------------------- |
| Name, email, phone, links | `DATA` object at top                   |
| Bio text                  | `DATA.bio` array                       |
| Stats bar numbers         | `DATA.stats`                           |
| Skills                    | `DATA.skills`                          |
| Services                  | `DATA.services`                        |
| Achievements              | `DATA.achievements`                    |
| Work experience           | `DATA.experience`                      |
| Projects                  | `DATA.projects`                        |
| Education                 | `DATA.education`                       |
| Fun facts                 | `DATA.funfacts`                        |
| Colors (light/dark)       | `LIGHT` and `DARK` objects             |
| 3D animation speed        | `t += 0.003` in `ThreeBackground`      |
| Particle count            | `dotCount = 1800` in `ThreeBackground` |

## 🌐 Deploy to Netlify (Free)

1. Run `npm run build`
2. Go to netlify.com/drop
3. Drag the `dist/` folder
4. Done — live link instantly!
