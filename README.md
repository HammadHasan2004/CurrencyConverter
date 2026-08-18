# Currency Converter

A simple web app to convert amounts between currencies in real time, with country flags for the selected currencies.

🔗 **Live Demo:** [currency-converter-lime-chi.vercel.app](https://currency-converter-lime-chi.vercel.app?_vercel_share=UJo3dlwRuJzXUaBx1ppMa4z2LRGTpvYh)

## Features

- Convert between 150+ currencies
- Auto-updating flag icons based on selected currency
- Defaults to USD → INR on load
- Real-time exchange rates fetched from a free public API

## Tech Stack

- HTML, CSS, JavaScript (no frameworks)
- [Currency API by fawazahmed0](https://github.com/fawazahmed0/exchange-api) for exchange rates
- [FlagsAPI](https://flagsapi.com/) for country flags

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main page structure |
| `style.css` | Styling |
| `app.js` | Handles dropdowns, flags, and exchange rate logic |
| `codes.js` | Currency-to-country code mappings |

## Running Locally

1. Clone the repo
2. Open `index.html` in your browser (no build step required)

## Deployment

This project is deployed on [Vercel](https://vercel.com) as a static site.
