# psyneulink.org

Source for the [PsyNeuLink](https://github.com/PrincetonUniversity/PsyNeuLink) project website, ported from WordPress. It is a small [Jekyll](https://jekyllrb.com/) site. The library documentation is a separate site, published from the PsyNeuLink repo.

**Status:** preview at <https://jonhanke-nam.github.io/psyneulink.org/>. psyneulink.org still points at WordPress.

## Editing

| To change | Edit |
| --- | --- |
| Page text | `index.md`, `tutorial.md`, `psyneuview.md` |
| The menu | `_data/nav.yml` |
| Colors and spacing | `assets/css/site.css` |
| Header and footer | `_layouts/default.html` |

## Publishing and the domain move

The site is already previewing on GitHub Pages. The rest hasn't been done yet.

1. If the repo moves to its long-term home, update `source_url` in `_config.yml` and turn on GitHub Pages there for the `main` branch.
2. Set `url` to `https://psyneulink.org` and `baseurl` to `""` in `_config.yml`.
3. Check the domain's existing DNS records, including any email (MX) records.
4. Add a `CNAME` file containing `psyneulink.org`, and point DNS at GitHub Pages.
5. Turn on "Enforce HTTPS" once GitHub has issued the certificate.
6. Keep WordPress running for about a month as a fallback, then export it and ask for it to be shut down.

## Domain

- Registrar: GoDaddy
- Renewal date: **2027-01-30**
- Account owner: to be confirmed
