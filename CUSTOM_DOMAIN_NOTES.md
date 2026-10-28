# Optional custom subdomain — NOT ACTIVE

**Illustrative name only:** `book.elanlalonde.com`.

Only Elan (or a domain administrator he explicitly authorizes) can approve and configure a subdomain under `elanlalonde.com`. A separate GitHub Pages preview does **not** automatically belong to his website or inherit its ownership.

## Sequence after authorization

1. Verify which person controls `elanlalonde.com` domain DNS and confirm written approval for hosting/branding.
2. In the dedicated GitHub Pages repository's **Settings → Pages**, specify the exact approved custom subdomain and follow GitHub's domain verification and HTTPS instructions. Configure the GitHub side **before** pointing DNS, to avoid a potential subdomain takeover.
3. The domain administrator adds a DNS CNAME for the exact subdomain; for the account in use, GitHub's documented target pattern is `annaalabaso.github.io` (exclude the repository name). Use the current instructions from GitHub and the DNS provider.
4. Allow for propagation, verify HTTPS and that the correct page loads; remove the custom domain if the preview is retired.
5. Do not use Elan's subdomain before he expressly approves; do not modify his Squarespace or registrar settings without permission.

Official docs: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

For a pre-approval concept, the safer choice is an independent preview URL on a new repository, not Elan's domain.