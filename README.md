# Listed

AI-powered resale listing generator for second-hand fashion.

Upload photos of an item → get a ready-to-edit listing (title, price, description, condition, tags) → open it in Vinted, eBay, Depop, Leboncoin, and other marketplaces.

Inspired by the flow in modern reseller tools, built as a single-file progressive web app.

## Features

- **Photo upload** — one or multiple images / videos
- **AI listing generation** — optional OpenAI vision (or offline samples)
- **Editable results** — title, price, description, condition, color, hashtags
- **Open in…** — deep links to Vinted, eBay, Depop, Leboncoin, Poshmark, Grailed, Vestiaire Collective (with App Store fallback)
- **Leave confirmation** — “You’re leaving Listed” before opening another app
- **Light / dark mode** — light blue accents in light mode, dark blue in dark mode
- **Account** — simple local profile (name + email, stored on device only)
- **History** — previous listings saved and reopenable
- **API settings** — paste an OpenAI-compatible key; “Add API” links to OpenAI’s key page
- **Installable** — Add to Home Screen on iPhone for an app-like experience

## Live demo

After you enable GitHub Pages:

`https://criminalviolence.github.io/resell.ai/`

## How to use

1. Open the app
2. Add photos of your item
3. Tap **Generate listing**
4. Edit anything you want
5. Copy or **Continue** → pick a marketplace

### Real vision (optional)

1. Settings (sliders icon) → Vision AI  
2. Get a key at [platform.openai.com/api-keys](https://platform.openai.com/api-keys)  
3. Paste it and Save  
4. Key stays only on your device

Without a key, the app uses realistic offline sample listings.

## Run locally

Open `index.html` in a browser, or:

```bash
npx serve .
