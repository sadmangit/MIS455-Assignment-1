# F1 Team Guide
MIS 455 — Assignment 1: Basic HTML & CSS

A simple 5-page static website about five famous Formula 1 teams, built with plain HTML5 and CSS3 (no frameworks, no JavaScript).

## Pages
| File | Team |
|------|------|
| `index.html` | Ferrari (home page) |
| `mercedes.html` | Mercedes |
| `redbull.html` | Red Bull |
| `mclaren.html` | McLaren |
| `williams.html` | Williams |

## Structure
```
f1-team-guide/
├── index.html
├── mercedes.html
├── redbull.html
├── mclaren.html
├── williams.html
├── css/style.css
├── images/          (team car photos + podium illustrations)
├── netlify.toml
└── README.md
```

## Images
- The car photo and the podium photo on each page are real photos supplied for this project.

## Assignment Checklist
- 5 linked pages with the same `<nav>` on every page
- 2+ paragraphs and 2+ images on every page
- One external stylesheet (`css/style.css`) linked from all pages
- CSS: margin, padding, background-color, color, font-size, font-family, box-shadow, border, border-radius, width, height, text-align, line-height, hover effects
- Two Google Fonts: Orbitron (headings) and Roboto (text)
- `display: flex`: nav bar, hero sections, Key Facts on Ferrari / Red Bull / Williams
- `display: grid`: Key Facts on Mercedes / McLaren
- HTML and CSS comments throughout
- External links (official team sites, Wikipedia, Formula1.com)

## Run locally
Open `index.html` in a browser.

## GitHub
```bash
git init
git add .
git commit -m "F1 Team Guide - MIS 455 Assignment 1"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/f1-team-guide.git
git push -u origin main
```

## Netlify
- Fastest: drag the project folder onto https://app.netlify.com/drop
- Or: Add new site > Import from GitHub, leave the build command empty, publish directory `.`
