# ServiceIQ — Certification Impact Dashboard

Interactive service engineer certification and performance analysis built from Practical assignment.xlsx.

## Run

Open `dist/index.html` in a browser. No installation or build step is needed.

## Deploy on Render

- Service type: Static Site
- Branch: main
- Build command: leave empty (or `echo ready` if a command is required)
- Publish directory: `dist`

## Data

`dist/data.js` contains an extracted workbook snapshot. Filters and metrics calculate in the browser; editing the original Excel workbook does not automatically refresh the snapshot. Methodology, excluded records and source limitations are documented inside the dashboard.

Features include zone/technology/status/month filters, certification cohorts, resolution trends, training threshold comparisons, engineer search and filtered CSV export.
