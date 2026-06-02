# Da Hill Reunion Website

**dahillreunion.com** — Forward in Power. Rooted in Love.

The official website for the Da Hill Reunion community — St. Nicholas Terrace, Harlem, NY.

---

## Structure

```
dahillreunion/
├── index.html              # Homepage
├── CNAME                   # Custom domain for GitHub Pages
├── css/
│   └── style.css           # Global styles
├── js/
│   └── main.js             # Global JavaScript
├── images/
│   ├── community-hero.jpg
│   ├── community-dancers.jpg
│   ├── community-block.jpg
│   ├── community-performer.jpg
│   ├── community-three.jpg
│   ├── community-couple-crown.jpg
│   ├── community-two-men.jpg
│   ├── community-mission.jpg
│   └── gallery-1 through gallery-10.jpg
└── pages/
    ├── history.html
    ├── events.html
    ├── gallery.html
    ├── entrepreneurs.html
    ├── heroes.html
    └── contact.html
```

## Deployment

Hosted on **GitHub Pages** at [dahillreunion.com](https://dahillreunion.com)

### To deploy:
1. Push this repo to GitHub under `sidartifax-cpu/dahillreunion`
2. Go to Settings > Pages > Source: Deploy from branch `main` / root `/`
3. Point GoDaddy DNS to GitHub Pages IPs (see instructions below)

### GoDaddy DNS Settings:
Add these **A records** pointing to GitHub Pages:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
Add a **CNAME record**:
```
www → sidartifax-cpu.github.io
```

---

Designed by [Moor Graphix](https://www.moorgraphix.com)
