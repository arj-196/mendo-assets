# mendo-assets

Public images served through jsDelivr, for places that can only load images from a CDN (Claude's inline widgets allow `cdn.jsdelivr.net`).

```
https://cdn.jsdelivr.net/gh/arj-196/mendo-assets@<tag>/<path>
```

Always reference a **tag**, never `@main`: jsDelivr caches branch URLs for days, while a tag URL is immutable. To change an image, commit it, push a new tag, and update whatever references the old tag.

| Path | What | Source | Referenced by |
|---|---|---|---|
| `kilo/` | Kilo's mood pictures | `ClientDeployment/kilo/art/make_kilo.py` | `ClientDeployment/kilo/skills/kilo/SKILL.md` (Pictures) |
