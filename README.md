# HCP Intelligence Decision Lab

Static, self-contained synthetic-data demo. No build step, dependencies, API keys, or network calls are required.

## Files for the existing GitHub repository

Upload/replace `index.html` and `DRLdemohcp.html` in the root of `kiranforgiven-ops/DRLdemoHCP`. The root `index.html` forwards visitors to `DRLdemohcp.html`.

## Enable GitHub Pages

1. Open `https://github.com/kiranforgiven-ops/DRLdemoHCP/settings/pages`.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. When deployment completes, the shareable app URL is `https://kiranforgiven-ops.github.io/DRLdemoHCP/`.

## Assistant limitations

The in-app assistant is a local, deterministic, rules-based prototype that answers from synthetic demo data. It is not connected to an external generative AI model. Prompts are not sent to a server or written into the event log. Do not enter personal, patient, customer, or confidential information.

All records and metrics are synthetic. The demo is not a production or client-validated system and must not be used to guide clinical decisions or represented as evidence of business impact.
