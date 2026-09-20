# Dear Reader privacy policy

A standalone static privacy-policy website for **Dear Reader**, published by
**Paper Glacier Studio**. This folder is ready to upload to its own public GitHub
repository and host on GitHub Pages using GitHub Free.

## Files

- `index.html` — the public privacy policy; edit the policy text here.
- `styles.css` — responsive styling using the extension's paper/burgundy palette.
- `.nojekyll` — serves the site as static files without Jekyll processing.
- `.gitignore` — ignores local macOS metadata.

No installation, JavaScript, build step, extension code, or API keys are needed.
Open `index.html` in a browser to preview it locally.

## Publisher and contact

- **Publisher:** Paper Glacier Studio
- **Privacy contact:** [hello@paperglacierstudio.com](mailto:hello@paperglacierstudio.com)
- **Hosting:** the default GitHub Pages address; no custom domain is required.

The policy includes:

- Local storage, API keys, reading events, preferences, and retention behavior.
- Article fetching, signed-in publisher cookies, and the named external services.
- Public commenter usernames included in discussion content sent to Anthropic.
- The Chrome Web Store Limited Use compliance statement.
- A separate notice about GitHub Pages' handling of website visitor IP addresses.

## Publish with GitHub Free

1. Use the public repository
   [Paper-Glacier-Studio/dear-reader-privacy-policy](https://github.com/Paper-Glacier-Studio/dear-reader-privacy-policy).
   The extension's separate repository can stay private.
2. Commit and push your changes, or upload this folder's **contents to the repository root**. `index.html` and
   `styles.css` should appear directly at the top level, not inside an extra
   `dear-reader-privacy-policy/` subfolder. Include `.nojekyll` if uploading with
   Git; plain HTML/CSS will also work if the browser uploader omits hidden files.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the **main** branch and **/(root)** folder, then save.
6. Wait for the Pages deployment to complete. Use the published HTTPS address
   displayed in Settings → Pages and enable **Enforce HTTPS** if available.
7. Open the address in a private/incognito browser window to confirm that it
   works without a GitHub login and the styles load correctly.

The default URL for this repository will be:

```text
https://paper-glacier-studio.github.io/dear-reader-privacy-policy/
```

This URL becomes live after you enable Pages and its deployment succeeds.
Use the site URL (not the `github.com/...` repository URL) in the Chrome Web Store
privacy-policy field. Also link it from the extension's in-app privacy page and
keep the extension repository's `PRIVACY.md` consistent with this public policy.

## Remaining publishing steps

- Push the updated policy and confirm GitHub Pages is enabled on `main` / `/(root)`.
- Open the published HTTPS URL without signing in and confirm the current contact
  address appears.
- Verify that `hello@paperglacierstudio.com` receives mail and replies use the
  intended studio alias.
- Enter the published URL and contact email in the Chrome Web Store dashboard.
- In the extension repository, synchronize `PRIVACY.md` and `public/privacy.html`
  with the contact email, public URL, Limited Use statement, and explicit
  disclosure of public commenter usernames. Replace the in-extension publication
  placeholder, then rebuild the extension package before uploading it.

## Updates

Edit `index.html` and push/upload the changes to `main`; GitHub Pages will
redeploy the site. Review the effective date when making substantive changes.
Only put information intended for the public in this repository.
