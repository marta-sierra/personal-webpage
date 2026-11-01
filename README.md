# Personal Webpage

**Live site:** [marta-sierra.github.io/personal-webpage](https://marta-sierra.github.io/personal-webpage/)

The personal site of Marta Sierra Obea: a one-page CV with my awards, hackathons, work experience and education. It has a terminal-inspired look and a light/dark toggle.

## Stack

There's no framework or build step. It's a single `index.html` with inline CSS and a bit of vanilla JavaScript:

- a light/dark theme toggle, with the choice saved in `localStorage`
- an info popover for the Cala Comet cohort
- highlighter marks that draw in as you scroll

The site is hosted on **GitHub Pages** from the `main` branch.

## Structure

```
index.html   # the whole site (markup, styles, scripts)
media/       # photos, logos and demo video thumbnails
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Contact

[martasierraobea23@gmail.com](mailto:martasierraobea23@gmail.com) · [LinkedIn](https://www.linkedin.com/in/marta-sierra-obea/)
