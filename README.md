# Pande Stationary Book Shop

Premium stationery storefront with a dark-luxury UI, CSS 3D visuals, lighting/glow, category filters, search, cart and WhatsApp order message.

## Files

- `index.html` — page structure, sections and content placeholders.
- `css/style.css` — all visual design, responsive layouts, lighting and 3D effects.
- `js/products.js` — product catalogue and category metadata. Edit products here first.
- `js/script.js` — rendering, search, filters, cart and WhatsApp order logic.

## First edit to make

Open `js/script.js` and replace:

```js
const WHATSAPP_NUMBER = '919999999999';
```

with the shop's real WhatsApp number (country code included, no `+` or spaces).

## Add a product

In `js/products.js`, add a new object inside `PRODUCTS`:

```js
{
  id: 999,
  category: 'Notebooks',
  type: 'notebook',
  name: 'New Notebook',
  price: 80,
  tag: 'New',
  desc: 'Short product description.',
  rating: '4.8'
}
```

## Price note

The listed prices are demo/example catalogue values to build the site structure. They should be replaced with the shop's actual selling prices before publishing.
