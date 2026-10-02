# wileybanting-site

One-page static site for Wiley Banting (modern gear for diabetes care). All purchases go to the Etsy shop: https://www.etsy.com/shop/WileyBanting

- `index.html`: page content, SEO meta, Organization JSON-LD
- `styles.css`: styles taken from the Etsy banner (grey ground, wide-tracked Jost caps, dotted leader line, ✱ mark)
- `favicon.svg`: asterisk mark

Product photos live in `assets/` (copied from the Etsy listings). The Open Graph share image still points at the Etsy banner URL.

Preview locally:

    python3 -m http.server 8742

Deploy: GitHub Pages from `main` (root). `CNAME` sets the custom domain to wileybanting.com.
