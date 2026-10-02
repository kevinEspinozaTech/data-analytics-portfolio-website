# Data Analytics Portfolio Website

A static portfolio site, published with GitHub Pages, that links my data analytics projects and my current automation work.

**Live site:** https://kevinespinozatech.github.io/

## Contents

| Section | Projects |
|---|---|
| Guided learning projects | [COVID-19 data exploration (SQL)](https://github.com/kevinEspinozaTech/covid19-global-exploratory-analysis-sql) · [COVID-19 Tableau dashboard](https://github.com/kevinEspinozaTech/covid19-global-dashboard-tableau) · [Nashville housing data cleaning (SQL)](https://github.com/kevinEspinozaTech/real-estate-data-cleaning-sql-server) · [Movie correlation analysis (Python)](https://github.com/kevinEspinozaTech/movie-box-office-drivers-python) · [Data professional survey (Power BI)](https://github.com/kevinEspinozaTech/data-careers-survey-dashboard-power-bi) |
| Work in progress | [rights-aware-video-clipping-pipeline](https://github.com/kevinEspinozaTech/rights-aware-video-clipping-pipeline) · [faceless-video-content-pipeline](https://github.com/kevinEspinozaTech/faceless-video-content-pipeline) · [ecommerce-marketing-decision-analytics](https://github.com/kevinEspinozaTech/ecommerce-marketing-decision-analytics) |

The SQL, Python, Tableau and Power BI projects follow courses by Alex The Analyst and are labelled as **guided learning projects** on the site. Each project's README gives the details and credits.

## Technologies

- HTML5, CSS (precompiled from Sass), JavaScript and jQuery
- [Massively](https://html5up.net/massively) template by HTML5 UP
- GitHub Pages (deployed from the `main` branch, root folder)

## Repository structure

```
.
├── index.html        # The portfolio page
├── assets/           # Template CSS, Sass sources, JavaScript and web fonts
├── images/           # Background and project thumbnails
├── .github/workflows/  # Weekly link check (lychee)
├── LICENSE.txt       # CC BY 3.0 license of the HTML5 UP template
├── README.txt        # Original HTML5 UP template readme and credits
└── README.md
```

## Quality checks

A GitHub Actions workflow ([`.github/workflows/link-check.yml`](.github/workflows/link-check.yml)) uses [lychee](https://github.com/lycheeverse/lychee) to check every link in `index.html` and this README. It runs every Monday, on every pull request, and on demand, and fails if a link is broken.

## Run locally

No build step is needed. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Changes in the 2026 refresh

- Moved the repository from `KevinEspinozaN/PagePortfolio` to `kevinEspinozaTech/kevinespinozatech.github.io`. The old GitHub Pages URL does **not** redirect.
- Updated all project links to the renamed repositories under `kevinEspinozaTech`.
- Labelled the course projects as *guided learning projects* and added a *work in progress* section.
- Added the Power BI project, which was missing from the site.
- Removed template placeholder content: a placeholder Twitter link, a demo date, `© Untitled`, and the unused template demo pages `elements.html` and `generic.html` with their demo images.
- Removed the phone number. Contact is by email only.
- Removed the LinkedIn links until the correct profile URL is confirmed.
- Fixed broken HTML in the footer and in one project heading.

## Credits and license

- Site design: **Massively by [HTML5 UP](https://html5up.net)** (@ajlkn), used under the [Creative Commons Attribution 3.0 license](https://html5up.net/license). See `LICENSE.txt` and `README.txt`. The template credit stays in the site footer as the license requires.
- Template components: [Font Awesome](https://fontawesome.com), [jQuery](https://jquery.com), [Scrollex](https://github.com/ajlkn/jquery.scrollex), [Responsive Tools](https://github.com/ajlkn/responsive-tools).
- Site content: Kevin Espinoza. The CC BY 3.0 template license does not cover the project content.

## Contact

**Kevin Espinoza**, Civil Engineer transitioning into Data Analytics and Automation
GitHub: [@kevinEspinozaTech](https://github.com/kevinEspinozaTech) · Email: [k.espinozano@gmail.com](mailto:k.espinozano@gmail.com)
