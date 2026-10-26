# Slicehub

A static, front-end-only pizza ordering site: a home page with menu sections,
three product pages, a cart, a hot-deals page and a login page. It was my first
HTML and CSS project.

## Pages

| File | What it shows |
|---|---|
| `Full-fledged-frontpage/Main_HTML-page.html` | Home page: thick-crust, thin-crust and vegetarian sections, plus the main navigation |
| `Full-fledged-frontpage/Product_page_1.html` to `_3.html` | Individual pizza pages with descriptions and images |
| `Full-fledged-frontpage/Cart_page.html` | Order summary layout |
| `Full-fledged-frontpage/Hot_deals.html` | Promotions page |
| `Full-fledged-frontpage/Login_HTML-page.html` | Login form layout |

Styling lives in `Main_css.css` and `Css_for_Product_page.css`.

## Running it

No build step and no dependencies. Open the home page in a browser:

```bash
open Full-fledged-frontpage/Main_HTML-page.html
```

## Status

This is a design and layout exercise, not a working shop. The cart, login and
product options don't process anything, there is no backend or database, and
no orders can be placed.

## What I'd improve next

- Move the repeated header, footer and product markup into shared templates.
- Make the cart store its state, for example with `localStorage`.
- Add a responsive layout for phone screens.
- Replace the placeholder images with licensed or self-made photos.

## Credits and licensing

The pizza photos in `Full-fledged-frontpage/` are not my own work. They were
collected from around the web as placeholders, and I haven't confirmed their
licences. Replace them before reusing this project anywhere beyond personal
study.
