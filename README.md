# Indian Heritage Club — One‑Page Website

This is a single `index.html` you can deploy on GitHub Pages or Netlify.

## Edit these placeholders
- Email in **Contact** section (`ihc@example.edu`)
- Google Calendar iframe `src=` (public calendar link)
- Google Form iframe `src=` (membership/RSVP embed link)
- Social links (Instagram, LinkedIn Group, Discord/WhatsApp)
- Leadership names + faculty advisor

## Deploy: GitHub Pages (quick)
1. Create a new GitHub repo (public): e.g. `ihc-website`.
2. Upload `index.html` to the root of the repo.
3. Go to **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` (root).
4. Wait for Pages to build; your site will be at `https://<your-username>.github.io/ihc-website/`.

### Custom domain (optional)
In **Settings → Pages**, set your domain (e.g., `ihc-yourcampus.org`). Add DNS `CNAME` to `<your-username>.github.io`.

## Deploy: Netlify (drag‑and‑drop)
1. Visit Netlify → **Add new site → Deploy manually**.
2. Drag the `index.html` file (or the whole folder) into the drop area.
3. Netlify gives you a live URL you can rename.

## Make Google Calendar public & embed
- In Google Calendar: **Settings → Select your calendar → Access permissions** → check *Make available to public* (or to anyone with the link, depending on your policy).
- Copy the **Embed code** `src=` and paste it into the calendar iframe.

## Embed Google Form
- In your Form: **Send → <> Embed** → Copy the `src=` URL and replace the placeholder in the `iframe` under “Membership / RSVP Form”.

## Test locally
Open `index.html` in a browser (double‑click). No build step needed.
