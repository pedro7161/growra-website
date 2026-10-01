# growra-website

Static landing page and privacy policy for **Growra** (`com.growra.app`), a free-form task app with a companion game.

Plain HTML with no build step, deployed to GitHub Pages by `.github/workflows/static.yml`. The deploy is manual-only (`workflow_dispatch`). Same shape as `shardmarch-website`.

| Page | Purpose |
|---|---|
| `index.html` | Landing page |
| `privacy-policy.html` | **Required by Google Play**, because the app has in-app purchases and ads |

The privacy policy URL goes in the Play Console store listing. Keep it honest: if the app's data handling changes (new SDKs, accounts, analytics), update the policy in the same pass.

No email or personal contact belongs on this site; contact goes through the Play Store listing.
