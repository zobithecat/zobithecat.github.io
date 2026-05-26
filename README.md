# zobithecat.github.io

Personal homepage for **Seonggeun Yoo** (유성근).

Live at: <https://zobithecat.github.io>

Plain HTML + CSS, no JavaScript, no build step.  Edit `index.html`
directly, commit, push — GitHub Pages serves it automatically off the
`main` branch.

## Layout

```
index.html    landing page (about, projects, patents, contact)
style.css     single stylesheet, dark-mode aware
```

## Editing

To update the patents list (e.g. when a new one is granted):

1. Open `index.html`.
2. Search for the `ol.patents` section.
3. Add a new `<li>` at the top of the list following the existing
   `patno · date · assignee` / `ptitle` pattern.

To add a project, copy one of the `<article>` blocks under the
"Selected open-source projects" section.

## Local preview

Any static server works; no build required.

```sh
python3 -m http.server 8000
# open http://localhost:8000
```
