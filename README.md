# RAMSAKAL INNOVATIONS — Website

A responsive, animated, static agency website for RAMSAKAL INNOVATIONS.

## Included
- Responsive one-page website with CSS motion and scroll reveal
- Custom SVG "RI" brand mark (`assets/logo.svg`) used in the header, footer, favicon and team profiles
- Founder portrait (`assets/archna-founder.png`)
- Live project links for Krishika Library and SmartSheet Solutions
- Team section with two named senior software engineers, each with a separate profile page:
  - `aarush-raj.html` (listed first)
  - `arjun-kumar.html`
  - Photos live in `assets/team/`
- Enquiry form that opens WhatsApp with the visitor's details pre-filled
- No paid APIs, database, build tools or backend required

## Run locally
Open `index.html` in a browser. For a local server, run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Free GitHub Pages deployment
1. Sign in to GitHub as `archnakumari-in`.
2. Create a new **public** repository named `ramsakal-innovations`.
3. Extract this ZIP. Upload the contents of this folder (`index.html`, `aarush-raj.html`, `arjun-kumar.html`, `styles.css`, `script.js`, `profile.js`, `README.md` and the `assets` folder) to the repository root. Do not upload the outer ZIP itself.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main**, folder **/(root)**, then click **Save**.
7. Wait for GitHub Pages to publish. Your site address will be `https://archnakumari-in.github.io/ramsakal-innovations/`.

## WhatsApp enquiry form
The form uses `https://wa.me/917571054064` and creates a pre-filled message. The visitor must press **Send** inside WhatsApp. This is intentional: it keeps the website free and does not silently store personal data. If this number is not registered on WhatsApp, change the number in `script.js`, `index.html` and the README.

## Before sharing with clients
- Confirm the contact number is the correct WhatsApp Business/contact number.
- Add each engineer's verified bio, experience and skills to their profile page (look for the HTML comment inside `.profile-copy`).
- Add client-approved screenshots, testimonials or case-study details only when you have permission and verified information.
- Consider adding a custom domain later; GitHub Pages hosting can remain free.
