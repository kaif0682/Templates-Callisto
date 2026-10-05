# Callisto Clinic

A responsive one-page website for **Callisto Clinic**, a gynecomastia specialist practice. The page presents the clinic's approach, treatment options, doctor profile, patient journey, results, FAQs, and booking call to action.

## Run locally

This is a static site with no build step or package installation required. Open `index.html` in a browser, or serve the folder with any local static-file server.

For example, with Python installed:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
.
|-- index.html       # Complete page markup, styles, and interaction scripts
`-- assests/         # Image assets (folder name is intentionally shown as it exists)
    |-- anatomy.svg
    |-- doctor.jpg
    |-- favicon.svg
    |-- hero-room.svg
    |-- og-image.png
    `-- treat-1.svg ... treat-4.svg
```

## Included features

- Responsive layout with a mobile navigation menu
- GSAP and ScrollTrigger entrance/scroll animations
- Lenis smooth scrolling
- FAQ accordion and booking form interface
- Structured-data markup for a medical clinic
- Google-hosted Instrument Sans and Instrument Serif fonts

## Image asset note

`index.html` currently references images from `assets/`, but the folder in this project is named `assests/`. Rename the folder to `assets`, or update the image paths in `index.html`, before publishing; otherwise the images, favicon, and social preview image will not load.

## Before publishing

Replace the placeholder contact details such as `[Name]`, `[phone]`, and `[address]`, then connect the booking form to the appropriate form handler or scheduling service.
