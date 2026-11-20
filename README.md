# EWRL 2027 website

Static conference website prepared for GitHub Pages. Navigation and information structure follow the MIT-licensed EWRL 2026 / Mini-Conf website, with a dependency-free implementation. No previous-year paper data, personal details, sponsors, branding images or location-specific notices are included.

## Publish

For https://ewrlc27.github.io, first create a GitHub organization named `ewrlc27` (subject to GitHub availability), then a public repository named `ewrlc27.github.io` in that organization. Upload this folder's contents to the repository root. Under Settings → Pages, choose Deploy from a branch, `main`, `/ (root)`, then Save.

For a repository on your existing account, use `ewrl-2027`; the default address is https://USERNAME.github.io/ewrl-2027/. All local links are relative and support both options.

## Editing

- `index.html`: overview, dates, organizers and sponsors
- `call.html`: call for papers and submission deadlines
- `calendar.html`: programme and speakers
- `papers.html`: accepted papers and poster information
- `help.html`: registration, venue, travel and contact
- `assets/site.css`: shared styling

August 2027 is explicitly tentative. Replace placeholders only with confirmed information. No submission or registration forms are active.

## Preview

Run `python3 -m http.server 8000` in this folder, then open http://localhost:8000.

## Optional custom domain

A github.io address needs no purchased domain. If ewrlc27.cc is chosen later, register it separately, verify ownership in GitHub, configure it in Pages settings and add the DNS records specified in GitHub's current documentation. No CNAME is included because a domain has not been selected or verified.

## Attribution

Reference: https://github.com/ewrl-org/ewrl-2026 and https://github.com/ewrl-org/ewrl-org.github.io. Original Mini-Conf MIT license retained in LICENSE.

## Current design

Soft coastal design with warm ivory, sage green, serif headings, pill navigation and an curved beach-and-hotel photo. Venue: Nyborg Strand, Nyborg, Denmark (confirmed by organizer). Exact August 2027 dates remain tentative.

Photo source: https://www.nyborgstrand.dk/en/press/
Original photo: https://www.nyborgstrand.dk/media/hecbqurm/nyborg_strand_250815_092329.jpg
The official press page welcomes use of its photographs in material about Nyborg Strand. Photo credit is included on every page. The photo is not covered by the code's MIT license.

Current hero image: organizer-supplied Nyborg Strand coastal photograph (`assets/nyborg-strand-coast.png`), shown at its full aspect ratio.
