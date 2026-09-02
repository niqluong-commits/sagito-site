# sagito-site

Public pages for Sagito, served by GitHub Pages.

This repository exists only to host documents that have to be reachable at a public
URL — chiefly the privacy policy, which both the App Store and Google Play require
before submission. **The app itself is in a separate private repository.** Nothing
here is source code and nothing here is secret.

Served at **https://privacy.sagito.app** via the `CNAME` file, which GitHub Pages
reads. The policy is the root of that subdomain rather than a page beneath it, so the
URL does not read `privacy.sagito.app/privacy/`.

The `niqluong-commits.github.io/sagito-site/` address still works and redirects.

`index.html` is **generated** from `docs/legal/PRIVACY.md` in the app
repository and should not be edited here — an edit would be overwritten and the two
would then disagree about what the app does. Change the markdown, regenerate, copy
the result across.

Published by QNL LTD, company number 09869549.
