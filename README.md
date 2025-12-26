# Mani Sankar — Portfolio (Improved single-page)

This is a responsive, accessible, and SEO-friendly single-page version of your portfolio. The personal contact details and profile image filename were kept as you requested.

Included files
- `index.html` — improved HTML with semantic structure, meta tags (Open Graph, Twitter), JSON-LD, and responsive image attributes.
- `styles.css` — mobile-first CSS with accessible focus styles and a responsive two-column layout for larger screens.
- `mani-sankar-profile.jpg` — (not included here) please keep this image in the same folder as `index.html`. Optionally provide a higher-resolution `mani-sankar-profile@2x.jpg` for retina displays.

How to use
1. Replace your existing `index.html` with the new `index.html` above or add these files to your repo root.
2. Ensure the profile image `mani-sankar-profile.jpg` is present in the same directory.
3. Commit and push to GitHub.
4. Deploy with GitHub Pages:
   - Go to your repository Settings -> Pages.
   - Select the branch (e.g., `main`) and folder (root) to publish.
   - Save. Your site will be available at `https://<username>.github.io/<repository>/` (or your custom domain if configured).

Testing locally
- Open `index.html` in a browser.
- Use browser devtools to emulate mobile widths and test keyboard navigation (Tab, Shift+Tab).
- Test Lighthouse audits (Accessibility, SEO, Best Practices).

Notes & next suggestions
- Add a high-resolution profile image `mani-sankar-profile@2x.jpg` for improved presentation on retina displays.
- Add a downloadable resume (PDF), LinkedIn and GitHub social links (Open Graph `sameAs` in JSON-LD).
- Consider deploying via a simple CI (GitHub Actions) to automate asset optimization and minification.
- Add real canonical URL in the `<link rel="canonical">` and `og:url` tags after you know the published site URL.

If you'd like, I can:
- Prepare a ready-to-commit patch (branch + commit) for this repository.
- Add social links and a resume download button.
- Convert this to a tiny static site using a bundler (Vite/React) or a simple static site generator.
