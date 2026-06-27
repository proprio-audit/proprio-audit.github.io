# ProprioGuard

Project page for ProprioGuard, built on the Bulma-based academic project page
template (in the lineage of [Nerfies](https://nerfies.github.io/)).

## Local preview

Serve the directory and open it in a browser, e.g.:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploying

This repo is intended to be hosted as a GitHub Pages **organization site**, so
it must live in a repo named exactly `proprio-guard.github.io` under a GitHub
organization (or account) literally named `proprio-guard`. That naming is
what gives the site the clean `https://proprio-guard.github.io` URL with no
personal account name in it.

Once pushed to that repo's default branch, enable GitHub Pages for the repo
(Settings → Pages → Deploy from branch) if it isn't already enabled
automatically.

## Filling in content

`index.html` contains `[PLACEHOLDER]` markers for the tagline, abstract,
method, results, acknowledgements, and BibTeX sections — replace them with
real project content and media.
