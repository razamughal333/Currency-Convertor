# 💱 Currency Converter

A simple and clean currency converter web app built with HTML, CSS, and vanilla JavaScript. Supports 150+ currencies with live exchange rates and country flag icons.

---

## Features

- Convert between 150+ world currencies
- Live exchange rates powered by [ExchangeRate API](https://www.exchangerate-api.com/)
- Country flag icons for each currency
- Clean and minimal UI

---

## Built With

- HTML5
- CSS3
- JavaScript (Vanilla)
- [Font Awesome 6](https://fontawesome.com/) — for icons
- [FlagsAPI](https://flagsapi.com/) — for country flags
- [ExchangeRate API](https://www.exchangerate-api.com/) — for live rates

---

## Project Structure

```
currency-converter/
├── index.html      # Main HTML file
├── style.css       # Styling
├── app.js          # Core logic & API calls
├── codes.js        # Currency-to-country code mappings
└── README.md
```

---

## How to Use

1. Clone or download the repository
2. Open `index.html` in your browser — no build step needed
3. Enter an amount, select your **From** and **To** currencies, and click **Get Exchange Rate**

---

## API

Exchange rates are fetched from:

```
https://api.exchangerate-api.com/v4/latest/{CURRENCY}
```

This is a free, open API — no key required.

---

## Preview

> Navbar with branding + a centered card with currency dropdowns, flag icons, and a convert button.

---

## Author

**Raza Ahmed**

**RA** — built as a frontend JavaScript practice project.
