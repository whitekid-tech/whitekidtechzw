# WhiteKid Tech — Portfolio

Single-file static site (`public/index.html`), deployed on Render as a Static Site.

## Deploy
1. Push this folder to a GitHub repo.
2. Render dashboard → **New +** → **Blueprint** → pick the repo (uses `render.yaml`).
   - Or **New +** → **Static Site** → Build Command: *(blank)* → Publish Directory: `public`.
3. Deploy. Your site goes live at `https://whitekid-tech.onrender.com` (name may vary).

## Contact form
Set `CONFIG.FORM_ENDPOINT` near the top of the `<script>` in `public/index.html`
(e.g. a Formspree URL) so messages are actually delivered.
