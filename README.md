# HumNote privacy policy hosting

Prepared for GitHub user `Leedson`. This page has not been deployed by the assistant.

1. Create a public repository named `humnote-privacy` under Leedson.
2. Upload this folder's `index.html` directly to the repository root and commit to `main`.
3. Open repository Settings > Pages.
4. Select Deploy from a branch, branch `main`, folder `/(root)`, and Save.
5. Wait for deployment to finish and open https://leedson.github.io/humnote-privacy/ in a private browser window.
6. Once the policy loads publicly, enter that URL in Play Console's Privacy policy field.

Only the privacy page needs to be uploaded to this repository. Keep the app's upload keystore and signing passwords private.

The canonical generated page is `release/privacy-policy.html`. If policy text changes, regenerate it with `node scripts/export-privacy-policy.js`, copy it to this folder as `index.html`, and upload the updated file.

Reference: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
