# LumnaTech Homepage (GoHighLevel)

Animated corporate homepage for LumnaTech, built for a GoHighLevel **Custom HTML/JS** element.

## Files

| File | Purpose |
|---|---|
| `lumnatech-homepage-ghl.html` | The code to paste into GHL (HTML + CSS + JS, all scoped to `#lumna-home`). |
| `preview.html` | Full-page wrapper for previewing locally in a browser. |
| `assets/` | Hero and section images, the LumnaTech logo, client logos (`assets/clients/`) and testimonial photos (`assets/testimonials/`). |

## Using it in GHL

1. Upload everything in `assets/` to the GHL Media Library.
2. Open `lumnatech-homepage-ghl.html` and edit **only** the `LUMNA_CONFIG` block at the top:
   - `links`: landing pages, WhatsApp link and the Home behaviour
   - `contact`: email and address shown in the footer
   - `images`, `clientLogos`, testimonial `photo`: replace each `assets/...` path with its GHL Media Library URL
   - `testimonials`: real customer testimonials only
3. Paste the whole file into a full-width Custom HTML/JS element, then Save and Publish.
