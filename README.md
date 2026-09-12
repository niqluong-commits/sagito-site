# sagito-site

The public pages for **Sagito**, served by GitHub Pages at **info.sagito.app**.

| Path | Page | Source of truth |
| --- | --- | --- |
| `/privacy` | Privacy notice | `docs/legal/privacy-public.html` in the app repo |
| `/invite`, `/gift`, `/swap` | Where a shared code lands | `docs/legal/join-public.html` in the app repo |
| `/` | A short index | this repo only |
| `/support` | App introduction and help | this repo only |

**For privacy and shared-code pages, edit the app repo, not this one.** Those pages are sourced from
`niqluong-commits/sagito` and copied here; `docs/legal/PRIVACY.md` records the route,
and `docs/legal/joinPage.test.mjs` checks the landing page still builds a code the app
will accept. A change made only here is a change the tests cannot see.

The three code paths serve the same file. It works out which kind of code it is from
the path it was served at, so a new code type needs a new directory here.

**It moved from `privacy.sagito.app` on 9 September 2026**, because GitHub Pages allows
one custom domain per repository and two documents needed two addresses. The old
subdomain should redirect rather than 404 — a privacy URL given to an app store ought
to keep working.
