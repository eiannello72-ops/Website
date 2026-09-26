# Enterprise AE Company Playbooks

One-page, company-branded sites showing research on a target company's product, ICP,
macro and micro sales plays, competition, value story, and a 30/60/90 plan
for the Enterprise AE role.

| Company | Folder |
| --- | --- |
| 1mind | [`1mind/`](1mind/index.html) |
| LogicMonitor (Rockies) | [`logicmonitor/`](logicmonitor/index.html) |
| Tiger Data (Mountain and Western) | [`tigerdata/`](tigerdata/index.html) |

## Deploying

Each site is a single static `index.html` with no build step.

- **Netlify drop:** drag the company folder (e.g. `1mind/`) onto https://app.netlify.com/drop
- **Netlify from Git:** set *Base directory* to the company folder, leave the build command empty,
  and set *Publish directory* to the same folder
- **GitHub Pages:** enable Pages on this repo and open `/<company>/`
