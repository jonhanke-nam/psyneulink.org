# psyneulink.org

Source for the [PsyNeuLink](https://github.com/PrincetonUniversity/PsyNeuLink) project website, ported from WordPress. It is a small [Jekyll](https://jekyllrb.com/) site. The library documentation is a separate site, published from the PsyNeuLink repo.

**Status:** private working copy. It is not published yet, and psyneulink.org still points at WordPress.

## Editing

| To change | Edit |
| --- | --- |
| Page text | `index.md`, `tutorial.md`, `psyneulink-view-2.md` |
| The menu | `_data/nav.yml` |
| Colors and spacing | `assets/css/site.css` |
| Header and footer | `_layouts/default.html` |

## Publishing and the domain move

Nothing here has been done yet.

1. Make the repo public, or move it to its long-term home, and update `source_url` in `_config.yml`.
2. Turn on GitHub Pages for the `main` branch.
3. Check the domain's existing DNS records, including any email (MX) records.
4. Add a `CNAME` file containing `psyneulink.org`, and point DNS at GitHub Pages.
5. Turn on "Enforce HTTPS" once GitHub has issued the certificate.
6. Keep WordPress running for about a month as a fallback, then export it and ask for it to be shut down.

## Domain

- Registrar: GoDaddy
- Renewal date: **2027-01-30**
- Account owner: to be confirmed
