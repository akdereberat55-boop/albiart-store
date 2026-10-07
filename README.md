# Albi Art SEO/indexing update

This update keeps the existing homepage design and styling intact.

Changes:
- Homepage product cards now point to local Albi Art product pages instead of directly to Etsy.
- 44 individual product pages were added under /products/.
- Each product page has its own title, meta description, canonical URL, Open Graph data and Product structured data.
- sitemap.xml now contains the homepage plus all 44 product URLs.
- robots.txt continues to reference the sitemap.

Deploy:
1. Replace the repository files with this package.
2. Keep CNAME unchanged.
3. Commit and push to GitHub Pages.
4. In Google Search Console, resubmit https://albiart.store/sitemap.xml.
5. Inspect https://albiart.store/ and a few /products/.../ URLs and request indexing for the homepage and key product pages.
