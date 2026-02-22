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

No build tools or external dependencies are required.

## Project Structure

```
.
├── .github/workflows/
│   └── deploy.yml        # GitHub Actions workflow for deployment
├── Images/               # Image assets
├── index.html            # Main website page
└── README.md
```

## Deployment

The site is automatically deployed to **GitHub Pages** using GitHub Actions.

### Workflow

The deployment workflow (`.github/workflows/deploy.yml`) is triggered by:

- **Push** to the `main` branch
- **Manual dispatch** from the GitHub Actions tab

### How It Works

1. The workflow checks out the repository
2. Configures GitHub Pages
3. Uploads the entire repository root as an artifact
4. Deploys the artifact to GitHub Pages

Only one concurrent deployment is allowed; new deployments wait for in-progress ones to finish.

## Local Development

To run the website locally, open `index.html` in a web browser. No build step is needed.

Alternatively, use any static file server, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Contact

- **Email:** [fundacja.museion@interia.pl](mailto:fundacja.museion@interia.pl)
- **Nowa Kronika Wałbrzyska:** [nowa.kronika.walbrzyska@gmail.com](mailto:nowa.kronika.walbrzyska@gmail.com)
