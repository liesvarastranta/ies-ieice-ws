# Advancing Information and Telecommunication Workshop

[![Event](https://img.shields.io/badge/Event-August%201--2%2C%202026-orange)](https://liesvarastranta.github.io/ies-ieice-ws/)
[![Location](https://img.shields.io/badge/Location-Yogyakarta%2C%20Indonesia-green)](https://www.google.com/maps/place/Sahid+Raya+Yogyakarta+Hotel+%26+Convention+Yogyakarta)
[![Format](https://img.shields.io/badge/Format-Hybrid-blue)](https://liesvarastranta.github.io/ies-ieice-ws/)

Official workshop website for the international collaboration between IEICE TC on IT (Japan), IES-PENS (Indonesia), and BRIN (Indonesia), focused on bridging theory and real-world application in information and telecommunication.

## Live Website

https://liesvarastranta.github.io/ies-ieice-ws/

## Event Snapshot

- Date: August 1-2, 2026
- Location: Sahid Raya Yogyakarta Hotel and Convention, Yogyakarta, Indonesia
- Format: Hybrid (onsite and virtual)
- Main collaborators:
  - IEICE TC on IT
  - IES - Politeknik Elektronika Negeri Surabaya (PENS)
  - BRIN - National Research and Innovation Agency

## Highlights

- Collaborative branding and section-based one-page layout
- Sticky desktop and mobile navigation
- Countdown timer to workshop opening
- Event details with map and venue card
- Yogyakarta destination carousel
- Two submission paths (IEICE track and IES/EDAS track)
- Speakers section with profile photos and scholar links
- Committee section with member headshots
- Visa information and contact section

## Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript

No build step is required.

## Repository Structure

```
ieice-workshop/
|-- index.html
|-- README.md
|-- LICENSE
`-- assets/
    |-- bg/
    |   |-- 1560-2.png
    |   |-- batik-kawung.jpg
    |   |-- wayang-2.png
    |   `-- wayang-2.svg
    |-- carousel/
    |   |-- borobudur.jpg
    |   |-- gudeg.jpg
    |   |-- keraton.webp
    |   |-- prambanan.jpg
    |   `-- tugu.webp
    |-- committee/
    |   |-- agus.jpg
    |   |-- amang.png
    |   |-- amma.jpg
    |   |-- galih.jpg
    |   |-- hamka.jpg
    |   |-- maya.png
    |   |-- nasrullah.jpg
    |   |-- naufal.jpeg
    |   |-- nogami.jpg
    |   |-- safira.jpg
    |   `-- shamim.jpeg
    |-- headshot/
    |   |-- brin.png
    |   |-- budi-brin.jpg
    |   |-- gede-pens.jpeg
    |   |-- ieice.png
    |   |-- jun-ieice.jpg
    |   |-- pens1.png
    |   `-- pens2.png
    |-- logo/
    |   |-- brin_logo.png
    |   |-- Google_Scholar_logo.svg
    |   |-- ieice.png
    |   |-- ies-2026-logo-ori.png
    |   |-- ies-2026-logo-white.png
    |   |-- ies-2026-logo.png
    |   `-- Logo_PENS.png
    `-- gunungan.png
```

## Run Locally

1. Clone the repository.
2. Open index.html directly in your browser.

Example:

```bash
git clone https://github.com/<your-org-or-user>/ieice-workshop.git
cd ieice-workshop
start index.html
```

## Deployment (GitHub Pages)

1. Push the repository to GitHub.
2. Open Settings > Pages.
3. Set source to branch main and folder root (/).
4. Save and wait for deployment.

## Content Update Guide

Common updates are all in index.html:

- Event date for countdown:
  - Update Date.UTC(...) inside updateCountdown().
- SEO and social metadata:
  - Update title, description, keywords, og:url, and image tags in head.
- Submission URLs:
  - IEICE track currently points to https://ken.ieice.org/ken/program/index.php?tgid=IT
  - IES track currently points to https://edas.info/
- Venue details:
  - Update venue text and the embedded Google Maps iframe URL.
- Contacts:
  - Update mailto links and any organizer text in the contact section.

## License

MIT License. See LICENSE.
