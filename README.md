# The Fit Standard

A single-page fitness site for The Fit Standard. It introduces the trainer, covers nutrition, training, and sleep, offers a training-plan ebook, shows client stories, and lists how to get in touch.

## Pages

The site is one page, `index.html`, with these sections:

- **Home** — banner, quote, and links to Facebook and Instagram
- **O meni** — short trainer introduction
- **Zdravlje** — tabs for prehrana (nutrition), trening (training), and san (sleep)
- **Plan treninga** — ebook description with a link to the training-plan PDF
- **Klijenti** — client slider
- **Kontakt** — studio address, phone, and email

## Contact

- Address: 14 Training Lane, Koregaon Park, Pune 411001, India
- Phone: +91 20 4850 7700
- Alternative phone: +91 20 4850 7701
- Email: hello@thefitstandard.com
- Alternative email: support@thefitstandard.com

## Stack

HTML, SCSS compiled to `css/stylesheet.css`, and vanilla JavaScript (`script.js` for navigation, the year in the footer, and the health tabs; `slider.js` and `assets/data/data.js` for the client slider).

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve .
```

To recompile styles while editing SCSS:

```bash
npm install
npm run compile:sass
```
