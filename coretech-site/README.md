# Core Tech Companies — Website

Built by [DJM Creative](https://djm-creative.com)

## File Structure

```
/
├── index.html          ← Main homepage
├── assets/
│   ├── styles.css      ← All styles
│   ├── main.js         ← Scroll animations & nav behavior
│   └── logo.png        ← Core Tech logo (transparent background)
└── README.md
```

## GitHub Pages Setup

1. Push all files to your GitHub repo (keep this flat structure — `index.html` at root)
2. Go to **Settings → Pages**
3. Set Source to **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://yourusername.github.io/repo-name`

## Custom Domain (coretechmke.com)

1. In GitHub Pages settings, add your custom domain: `coretechmke.com`
2. At your domain registrar, add these DNS records:
   - A record → `185.199.108.153`
   - A record → `185.199.109.153`
   - A record → `185.199.110.153`
   - A record → `185.199.111.153`
   - CNAME `www` → `yourusername.github.io`
3. Check "Enforce HTTPS" in GitHub Pages settings

## Swapping Placeholder Photos

Each service card image has a `<!-- PHOTO NOTE -->` comment above it in `index.html`.
Replace the `src` URL with the path to your real photo, e.g.:

```html
<!-- Before -->
<img src="https://images.unsplash.com/photo-xxx" alt="...">

<!-- After (place photos in assets/images/) -->
<img src="assets/images/managed-it-milwaukee.jpg" alt="...">
```

## SEO Checklist (already built in)

- [x] Title tag — service + location
- [x] Meta description with NAP keywords
- [x] LocalBusiness JSON-LD schema
- [x] Canonical tag
- [x] Open Graph tags
- [x] Semantic H1/H2/H3 hierarchy
- [x] Descriptive alt text on all images
- [x] Service area content (suburbs listed)
- [x] Mobile responsive
- [ ] Submit sitemap to Google Search Console after launch
- [ ] Verify Google Business Profile matches NAP on site
- [ ] Replace placeholder testimonials with real Google reviews

## Monthly Maintenance (DJM Creative)

- SEO performance monitoring (Semrush)
- Content updates and blog posts
- Security & uptime monitoring
- Google Business Profile management
- Analytics reporting
