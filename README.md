# Second Plaza Tower

Luxury apartment rentals in Edgewater, Miami. A static marketing site for [Melo Group](https://melogroup.com), redesigned from the live WordPress site at [secondplazatower.com](https://secondplazatower.com).

**222 NE 25th Street, Miami, FL 33137** · (305) 438-3733 · info@secondplazatower.com

## Preview locally

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

Any static file server works — there is no build step, WordPress, or JavaScript framework. The page is a single `index.html` with Tailwind via CDN, the same pattern used by sibling Melo property sites (Art Plaza Tower, 25 Mirage, Square Station).

## Structure

| Path | Purpose |
| --- | --- |
| `index.html` | Full single-page site |
| `images/` | Logos, favicon, and photography from the live site |
| `floorplans/` | Unit layouts (full-size PNGs from the live site) |
| `brochure.pdf` | Property brochure (`Second-Plaza_brochure.pdf`) |
| `CNAME` | `secondplazatower.com` for GitHub Pages |

The contact form opens a pre-filled `mailto:` to info@secondplazatower.com. No backend is required.
