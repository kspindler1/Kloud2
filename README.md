# Kloud — GitHub Pages deployment

Prepared for: https://kspindler1.github.io/kspindle/

## Publish
1. Extract this ZIP.
2. Upload the complete contents to the root of `kspindler1/kspindle`.
3. In GitHub, open Settings → Pages.
4. Choose Deploy from a branch, select the publishing branch and `/ (root)`, then save.
5. After deployment finishes, open the URL above and hard-refresh once.

The QR code automatically uses the deployed site root. Phone users can scan it and choose Add to Home Screen or Install app.

## Included demos
- Clinical Trial Consistency Review dashboard
- Safety & Tumor Response dashboard
- CQL Harmonizer Mode A video
- CQL Builder Mode B video

## Genie and security
The main Kloud Genie answers from its built-in Kloud knowledge and can optionally call its configured public browser-based LLM providers. Do not enter patient-identifiable, confidential, credential, or proprietary information into public model modes.

The Protocol Consistency dashboard includes screens intended for a separate authenticated MCP/backend connector. GitHub Pages hosts static files only, so server-side Apollo, Veeva, SharePoint, Anthropic, and Direct Line operations require an approved HTTPS backend. Never place API keys or client secrets in this repository or `kloud-config.js`.
