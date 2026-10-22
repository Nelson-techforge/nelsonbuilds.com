# Nelsonbuilds Technology — GitHub Pages Portfolio

## Publish the site
1. Sign in to GitHub using your existing account (`Nelson-techforge`).
2. Create a **public** repository named `nelsonbuilds-portfolio`.
3. Upload `index.html`, `styles.css`, and `script.js` to the repository root (not just the ZIP).
4. Open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Your URL will look like `https://nelson-techforge.github.io/nelsonbuilds-portfolio/` after GitHub publishes it.

GitHub Pages is static hosting. It does not run PHP or send email directly.

## Connect the form to email for free
The old `inquiries@nelsonbuilds.com.ng` mailbox is unavailable while the domain/hosting access is expired. Use an accessible Gmail inbox until domain/email access is restored.

1. Sign in at https://script.google.com/ and create a new project.
2. Paste `google-apps-script/Code.gs` into its `Code.gs`.
3. In Project Settings → Script Properties, add `CONTACT_RECIPIENT` with an inbox you can access.
4. Deploy → New deployment → Web app. Choose Execute as **Me** and access **Anyone**; review authorization and deploy.
5. Copy the web app URL ending in `/exec`.
6. Edit `script.js` and set `CONTACT_ENDPOINT` to that URL. Commit the change to GitHub.
7. Submit a test inquiry and verify the message actually arrives in the inbox/spam folder. Do not claim delivery is working before this test.

## Important
- Browser `no-cors` submission cannot verify that the email arrived; check the inbox directly. This is a simple starter, not a hardened high-volume form service.
- Apps Script has usage quotas and may require account authorization.
- Never commit passwords or API keys.
- The project cards are clearly labelled concepts. Replace them with genuine work, screenshots and working links before presenting them as completed client projects.
- GitHub Pages will not restore `nelsonbuilds.com.ng` or its expired mailbox; reconnecting that domain requires regaining domain/DNS control.
