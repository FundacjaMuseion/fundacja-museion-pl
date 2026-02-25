# Fundacja Museion

Official website of **Fundacja Museion** — a Polish non-profit foundation dedicated to cultural heritage preservation, regional history documentation, and publishing, based in Wałbrzych, Poland.

## About the Foundation

Fundacja Museion was established by notarial act on February 20, 2012. The foundation is apolitical and non-denominational, operating under Polish law. Its mission focuses on cultural heritage, science, and culture, with particular emphasis on the Wałbrzych region.

**Headquarters:** ul. Jana Brzechwy 11/1a, 58-300 Wałbrzych, Poland

## Website Sections

- **Aktualności** — News and announcements
- **O nas** — About the foundation, including excerpts from its statute
- **Nowa Kronika Wałbrzyska** — Annual publication chronicling the Wałbrzych region (volumes, information, and links)
- **Oficyna Wydawnicza** — Publishing office promoting knowledge about the Wałbrzych region, with four publication series:
  - Biblioteka Wałbrzyska
  - Wałbrzyska Historia
  - Wałbrzyski Region
  - Wałbrzyskie Portrety Biograficzne
- **Promocje i wydarzenia** — Promotions and events organized by the foundation
- **Wizytówka** — Contact card

## Tech Stack

This is a static website built with:

- HTML
- CSS (embedded)
- Vanilla JavaScript
- [Jekyll](https://jekyllrb.com/) — used by GitHub Pages to build and publish the site

No external frontend dependencies are required.

## Project Structure

```
.
├── www/
│   ├── images/             # Image assets
│   └── index.html          # Main website page
├── _config.yml             # Jekyll configuration for GitHub Pages
└── README.md
```

## Deployment

The site is automatically deployed to **GitHub Pages** using the built-in GitHub Pages integration. Deployment is configured via the repository's **GitHub Pages settings** (Settings → Pages), with Jekyll handling the build step.

## Local Development

To run the website locally, you can open `www/index.html` directly in a web browser, or use Jekyll:

```bash
gem install jekyll bundler
jekyll serve
```

Then visit `http://localhost:4000` in your browser.

Alternatively, use any static file server:

```bash
cd www
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Contact

- **Email:** [fundacja.museion@interia.pl](mailto:fundacja.museion@interia.pl)
- **Nowa Kronika Wałbrzyska:** [nowa.kronika.walbrzyska@gmail.com](mailto:nowa.kronika.walbrzyska@gmail.com)