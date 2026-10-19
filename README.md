# QuotePlace Images

Image quotes for QuotePlace. Images live here, the site references them by CDN URL.

## Adding an image
1. Upload the image file into `images/` (keep names short, lowercase, no spaces, e.g. `aristotle-well-begun.jpg`).
2. Use this URL in the quote's `img` field:

```
https://cdn.jsdelivr.net/gh/QuotePlaceOrg/quoteplace-images@main/images/<filename>
```

## Notes
- This repo must stay PUBLIC - jsDelivr only serves public repos.
- Keep each file under 50 MB (jsDelivr limit) and the repo under ~1 GB total.
- Prefer compressed JPG/WebP (~100-300 KB per quote image).
