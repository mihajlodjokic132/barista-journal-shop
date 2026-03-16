# Barista Journal Shop

Product data for the Barista Journal iOS app's affiliate shop. The app fetches `products.json` from this repo at runtime.

## Usage

Edit `products.json` to add, update, or remove products. Changes go live as soon as you push — no app update needed.

## Schema

```json
{
  "id": "unique-slug",
  "title": "Product Name",
  "description": "Short description shown in the app",
  "imageURL": "https://...",
  "affiliateURL": "https://your-affiliate-link",
  "category": "equipment | beans | merch",
  "priority": 1
}
```

- **id** — Unique identifier (use slug format)
- **title** — Product display name
- **description** — 1-2 sentence description
- **imageURL** — Product image (recommended 600x400)
- **affiliateURL** — Your affiliate link
- **category** — Used for filter tabs in the app
- **priority** — Lower number = shown first within category
