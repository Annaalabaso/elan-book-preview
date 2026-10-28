# Elan LaLonde — Leadership Book Landing Page (Draft Preview)

**Status:** unapproved concept only. Not an authorized client website, published book offer, or functional lead-generation funnel.

## Files

- `index.html` — self-contained static webpage, ready for GitHub Pages. No external build or dependencies.
- `CUSTOM_DOMAIN_NOTES.md` — optional custom-domain guidance for when Elan expressly approves use of his domain.

## Publish a temporary GitHub Pages preview

1. In the GitHub account `Annaalabaso`, create a **new public** repository named `elan-book-preview` (do not reuse an unrelated client or project repository). GitHub Pages sites in a public repo are publicly accessible, even with a `noindex` meta tag.
2. Upload `index.html` at the repository root (plus this README optionally).
3. Open **Settings → Pages → Build and deployment → Deploy from a branch**. Select `main` and `/ (root)`, then Save.
4. Wait for GitHub to show the deployed URL in **Settings → Pages**. The expected URL format is `https://annaalabaso.github.io/elan-book-preview/`; **this is not a live URL until published and verified**.
5. Test on mobile and desktop. The page deliberately shows a review banner, a provisional book cover/title, and an inert email form.

## What must be approved before launch

- Book title, offer, wording, cover, and Elan's explicit permission to publish the page.
- Exact brand colors/fonts and any actual portraits, logos or testimonial rights.
- A real email signup provider, consent language, privacy policy, and data handling. The current form intentionally captures no data.
- A working, correct 60-minute Calendly link; the current CTA goes to his existing coaching page, not direct booking.
- Final accessibility and mobile QA; page metadata, social image, analytics approval and indexing policy.
- Hosting and domain ownership. For production, consider deploying directly within his existing Squarespace site to avoid unnecessary infrastructure.

## Notes

`<meta name="robots" content="noindex,nofollow,noarchive">` reduces normal search-engine indexing, but does not make the page private; anyone with the URL may view it. Use only if a public preview is acceptable. Do **not** collect emails or present this as a live pre-order/free-book offer.