# 🧳 Trillo — Your all-in-one booking

[🔗 Live demo](https://trelloeyas.netlify.app/) · ![Live badge](https://img.shields.io/badge/Live-YourSite-brightgreen)

## Overview

**Trillo** is a sleek, responsive hotel booking interface built to practice techniques from **“Advanced CSS and Sass: Flexbox, Grid, Animations and More!”** by [Jonas Schmedtmann](https://codingheroes.io/).  
It focuses on modular SCSS architecture, Flexbox layout patterns, reusable components, and subtle UI animations.

---

## Features

- ✅ Pixel-perfect, responsive layout (sidebar + content)
- 🧩 Component-based **SCSS** (variables, mixins, partials)
- 🧱 **Flexbox** for major layout + utility classes
- ✨ Micro-interactions (hover, active states, shadows)
- 🎯 Accessible semantic HTML structure
- 🧰 Simple **NPM/Sass** workflow

---

## Tech Stack

- **HTML5**
- **Sass (SCSS)**
- **Flexbox**
- (Optional) **Node/NPM** for compiling Sass

---

## Project Structure

```bash
Trillo-Advance-CSS/
├─ css/
│  └─ style.css              # Compiled CSS
├─ img/                      # Images (hero, avatars, icons…)
├─ sass/
│  ├─ abstracts/             # _variables, _mixins, _functions
│  ├─ base/                  # _base, _typography, _utilities
│  ├─ components/            # _button, _list, _user-reviews, _cta...
│  ├─ layout/                # _header, _sidebar, _content, _grid
│  ├─ pages/                 # _home (page-specific styles)
│  └─ main.scss              # Root Sass file that imports everything
├─ index.html
├─ package.json
└─ package-lock.json
