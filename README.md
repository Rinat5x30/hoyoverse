# HoyoPlay — Landing Page Clone

A pixel-perfect recreation of the **HoyoPlay** launcher landing page, built with pure HTML and CSS. This project was created as a frontend practice exercise to replicate a real-world product UI.

---

## Preview

![HoyoPlay Landing Page](assets/img/hoyoplay.png)

---

## About

HoyoPlay is the official game launcher by [HoYoverse](https://www.hoyoverse.com/), used to manage and launch titles such as Genshin Impact, Honkai: Star Rail, and Zenless Zone Zero.

This repository contains a **static front-end clone** of the launcher's landing page — no backend, no frameworks, just clean HTML and CSS.

---

## Tech Stack

| Technology | Purpose            |
|------------|--------------------|
| HTML5      | Markup & structure |
| CSS3       | Styling & layout   |

---

## Project Structure

```
hoyoplay/
├── index.html          # Main page
├── assets/
│   ├── base.css        # Global styles
│   └── img/            # Images & video assets
├── .env.example        # Environment variable template
├── .gitignore
└── README.md
```

---

## Getting Started

No build tools required. Just open the project in your browser:

```bash
# Clone the repository
git clone https://github.com/Rinat5x30/hoyoverse.git

# Open in browser
open index.html
# or on Windows:
start index.html
```

---

## Security

This project includes the following client-side security headers via `<meta>` tags:

- **Content-Security-Policy** — restricts resource loading to same-origin only
- **X-Content-Type-Options** — prevents MIME-type sniffing
- **X-Frame-Options** — blocks clickjacking via iframes
- **Referrer-Policy** — controls referrer information sent with requests
- **Permissions-Policy** — disables access to camera, microphone, and geolocation

---

## License

This project is for **educational purposes only**. All design assets, branding, and imagery belong to [HoYoverse](https://www.hoyoverse.com/). Not affiliated with or endorsed by HoYoverse.

---

## Author

**Rinat Aghayev** — [GitHub](https://github.com/Rinat5x30)
