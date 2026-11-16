# MUKA-MUKA Demo

A simple demo site at **https://demo.mukamuka.my**, separate from the main website (https://mukamuka.my, repo `emanzulx/mukamuka`).

- One file: `index.html` (HTML, CSS and JavaScript together). No build step.
- Hosted on Vercel as its own project. Every push to `main` goes live automatically.
- Marked `noindex`, so search engines don't list it next to the main site. Remove that line from `index.html` if this becomes a real public site.

## Preview locally

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.
