# HCP Intelligence Decision Lab

Static, self-contained synthetic-data demo based on the HCP Intelligence pitch-deck workflow. No build step, dependencies, API keys, or network calls are required.

## What this prototype demonstrates

- Full synthetic HCP roster, weighted allocation and brick-level reconciliation.
- 1,000 seeded resamples per brick, with an 80% interval whose width is adjusted using a separate synthetic calibration subset.
- Blind synthetic hold-out metrics and a side-by-side comparison with an existing-call-frequency proxy; acceptance thresholds can be set before reviewing results.
- Synthetic data-observability and failure-mode checks for roster match, dense territories, institutional mix, new-brand evidence, cross-brick leakage, substitution and potential saturation.
- Frequency-capped tour-plan scenarios, reason-coded local overrides, CSV export and scenario comparison.
- A proposed matched-territory-pair pilot protocol with a 90-day call-share primary endpoint, pre-registration snapshot and editable break-even arithmetic.
- A local, deterministic rules-based assistant, claims register and browser-local audit events.

All records and outcomes are synthetic. Small audit samples are intentionally identified as unstable; a calibration split does not establish real-world calibration. The pilot screen records design assumptions only and does not simulate or claim results.

## Not implemented

This static demo does not connect to CRM, sales, medical/public-professional or audit data; provide live source fusion; run an independently powered pilot; establish causal impact or ROI; implement authenticated rep workflows; or provide production privacy, security, compliance, data-retention or deletion controls. Client ownership, DPA, lawful basis, source rights, security review and commercial terms require separate agreement and implementation.

## Files for the existing GitHub repository

Upload/replace `index.html` and `DRLdemohcp.html` in the root of `kiranforgiven-ops/DRLdemoHCP`. The root `index.html` forwards visitors to `DRLdemohcp.html`.

## Enable GitHub Pages

1. Open `https://github.com/kiranforgiven-ops/DRLdemoHCP/settings/pages`.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. When deployment completes, the shareable app URL is `https://kiranforgiven-ops.github.io/DRLdemoHCP/`.

## Assistant limitations

The in-app assistant is a local, deterministic, rules-based prototype that answers from synthetic demo data. It is not connected to an external generative AI model. Prompts are not sent to a server or written into the event log. Do not enter personal, patient, customer, or confidential information.

All records and metrics are synthetic. The demo is not a production or client-validated system and must not be used to guide clinical decisions or represented as evidence of business impact. Do not enter real HCP, customer, patient or confidential information.
