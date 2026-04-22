# Nexu landing page — README v2 (copy review)

Lean README draft of the nexu landing page, broken out for text-only review.

## Files

- `nexu-readme-v2.md` — the actual copy draft (edit this to iterate)
- `index.html` — live preview wrapper (renders the .md via marked.js)

## Preview

Every push to `main` that touches this folder auto-deploys the preview to Cloudflare Pages:

- **Live preview:** https://nexu-readme-review.pages.dev
- **Raw Markdown:** [nexu-readme-v2.md](./nexu-readme-v2.md)

## How to iterate

1. Edit `nexu-readme-v2.md` directly on GitHub or locally
2. Commit + push to `main` (or open a PR + merge)
3. GitHub Actions rebuilds the Cloudflare Pages site (~30s)
4. Refresh https://nexu-readme-review.pages.dev/?v=$(date +%s)

## Status

- Draft · 707 words · text-only review pass
- Does NOT touch the live landing page (`nexu-narrative-preview.pages.dev`) until copy locks

## Related

- Live landing: https://nexu-narrative-preview.pages.dev
- GTM repo (production landing): https://github.com/nexu-io/gtm-engineering
