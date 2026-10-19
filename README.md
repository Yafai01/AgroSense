# AgroSense

A single-page front-end prototype for **AgroSense**, a concept agri-tech service that supplies IoT farm sensors to Indian farmers under a cost-sharing model (the farmer pays 60% and the company co-invests 40%, with one year of free service). The whole site is one self-contained `index.html` with inline CSS and JavaScript. It has no build step and no backend.

> **Note:** This is a design and UI prototype. The company details, statistics, testimonials, prices, contact information, and farmer records in it are sample content. The contact form only validates its fields and shows a confirmation message. Nothing is sent anywhere.

## Features

- **Client-side page switching** between Home, About, Services, Products, Dashboard, and Contact views, with no page reloads
- **Home page** with a hero section, a mock live sensor card (soil moisture, temperature, humidity, pH), an explanation of the 60/40 co-investment model, a five-step "how it works" flow, benefits, and testimonials
- **Products catalogue** of sensor and controller hardware, each with a spec list and the farmer's share of the price
- **Services overview** covering installation, app training, technician visits, support, analytics reports, weather alerts, and crop advisory
- **Dashboard** with a table of farmer installations. You can search it by name, phone, location, or product, and filter it by status (Installed / Pending / Scheduled); summary counters update as you go.
- **Contact form** with required-field validation and a success message
- **Responsive layout** with a mobile navigation menu and a dark theme

## Tech stack

- HTML5, CSS3 (custom properties, flexbox/grid, media queries)
- Vanilla JavaScript
- Google Fonts (Syne, DM Sans)

## Getting started

Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/Yafai01/AgroSense.git
cd AgroSense
# open index.html directly, or serve it locally:
python -m http.server 8000   # then visit http://localhost:8000
```

## Project structure

```
index.html   Complete site: markup, styles (<style>) and scripts (<script>)
```

The dashboard's sample data is in the `farmers` array at the bottom of `index.html`.
