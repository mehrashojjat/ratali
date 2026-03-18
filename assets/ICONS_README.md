Place the provided icon files in the repository using these exact paths/names:

- Root favicon (used by browsers): `favicon.ico`
- Social preview image (used by Open Graph / Twitter): `images/social-icon.png`

Notes:
- The HTML head in `index.html` was updated to reference those paths.
- If you have a different filename, either rename the file to match the paths above, or update the `og:image` / `twitter:image` and `<link>` hrefs in `index.html` accordingly.
- For best social previews use a PNG at 1200x630 or similar wide image; the `apple-touch-icon` entry uses the same file by default but you can supply a dedicated 180x180 PNG if you prefer.

If you want, I can add the actual files (`favicon.ico` and `images/social-icon.png`) into the repo now — upload them here or tell me where they are and I'll place them for you.