# Gan Labs Docs

A static website of visual HTML explainers for the lab's papers, pipelines and tools.

- `index.html` is the catalogue. Add one `<li>` per doc.
- `pages/<slug>.html`: one standalone page per doc. Each page is self-contained HTML; Mermaid diagrams load from jsDelivr.

There is no build step. Any static host can serve the folder: GitHub Pages (Settings → Pages → `main` / root), Vercel or Cloudflare Pages.

**Adding a doc:** write `pages/<slug>.html`, link it from `index.html`, then commit.
