# source_spine

Destination for Spine assets extracted by [apk2source](https://github.com/vladleopold/apk2source).

## Layout

```
<game-slug>/
  _index.json                 stats + skeleton entries
  <skeleton>/
    <skeleton>.json           Spine skeleton export
    <skeleton>.skel.bytes     Binary format
    <skeleton>.atlas          Atlas (page names rewritten)
    <page>.png                Texture pages
    _meta.json                sha256, spine version, provenance
```

See [LEGAL.md](https://github.com/vladleopold/apk2source/blob/main/docs/LEGAL.md).
