# Fabio — Personal Website (Dark) with Private and Unlisted Sections

This starter is a dark-themed static site using **Tailwind (CDN)** and **Alpine.js**.
It includes a public site, a linked **/private/** section, and an unlisted **/hihim/** section (no password).

## Structure

```
/
  index.html
  /projects/
    index.html
    project-foo.html
  /private/          # linked from navbar (shared private content like trips, theater, urbex)
    index.html
    date-me-doc.html
    urbex.html
    trips.html
    theater.html
  /hihim/            # secret/unlisted (not linked anywhere)
    index.html
    date-me-doc.html
    urbex.html
  /assets/
    /urbex/          # put your JPGs here
  /demos/            # future interactive demos
  netlify.toml
```

## Notes

- There is **no password protection**; `/hihim/` is simply unlisted. If you want a password later, add a `_headers` file.
- To change theme colors, edit Tailwind classes directly in HTML (e.g., `bg-slate-950`, `text-slate-100`).

## Deploy

Same steps as before: push to GitHub, then import the repo on Netlify.
