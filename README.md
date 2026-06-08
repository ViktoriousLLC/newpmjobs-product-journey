# NewPMJobs Product Journey

NewPMJobs is a daily job-alert tool for product managers: pick the companies you want to work for, and every morning it emails you the new, relevant PM roles, pulled from each company's own careers page and filtered down to what actually fits. The part worth knowing is who built it and how.

- **One product, end to end:** scraping, a self-healing data pipeline, a web app, a daily email and full monitoring, all live and serving real users.
- **Built by a PM, coded by AI:** every product, design and architecture decision was a product manager's; AI tools wrote the code under that direction.
- **Reliability treated as a feature:** most of the effort went into catching silent failures (a broken source, a quiet zero, a missed email) before a user ever notices.
- **The proof in numbers:** page speed went from 49 to 100, sub-second data calls replaced multi-minute browser scrapes and the catalog grew to 519 companies across 7 hiring platforms.

## Read the full journey

**[Open the full, styled journey](https://viktoriousllc.github.io/newpmjobs-product-journey/)** : 33 phases grouped into 6 stages, with the architecture and the decision behind each step.

(If GitHub Pages is not enabled yet, just open `index.html` in a browser; that file is the page.)

## The product

![The tracked-companies dashboard](images/product-dashboard.png)

![The NewPMJobs homepage](images/product-home.png)

## Architecture

[![System architecture](images/architecture-reactflow.png)](images/architecture-reactflow.png)

## Maintaining this

The published page is `index.html` (a single self-contained file). To add a new milestone, edit `index.html` and the matching image in `images/`, then commit and push. There is no build step.
