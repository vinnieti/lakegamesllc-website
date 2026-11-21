# Lake Games LLC — Studio Website

Official static website for **Lake Games LLC** (`https://lakegamesllc.com`), creators of **Last Roll**.

## Pages
- `index.html` — Studio & Last Roll showcase, company details, and contact information
- `privacy.html` — App Store & Google Play compliant Privacy Policy (`#delete-account` anchor for Google Play account deletion URL)
- `terms.html` — Terms of Service
- `404.html` — Custom 404 page
- `CNAME` — Custom domain routing (`lakegamesllc.com`)

## GitHub Pages & Custom Domain Setup
1. In GitHub repository **Settings → Pages**, set **Source** to **Deploy from a branch**, **Branch** to `main`, and folder to `/ (root)`.
2. At your DNS registrar for `lakegamesllc.com`, configure:
   - `A` records for `@`:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - `CNAME` record for `www`: `vinnieti.github.io`
3. Once DNS propagates, enable **Enforce HTTPS** in **Settings → Pages**.

## Store & OAuth Verification URLs
- **Homepage / Support URL:** `https://lakegamesllc.com/`
- **Privacy Policy URL:** `https://lakegamesllc.com/privacy.html`
- **Account Deletion URL (Google Play):** `https://lakegamesllc.com/privacy.html#delete-account`
- **Terms of Service URL:** `https://lakegamesllc.com/terms.html`
