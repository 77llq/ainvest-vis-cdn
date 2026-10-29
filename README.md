# AInvest visualization CDN assets

Public assets for AInvest visualization integrations.

## Standard Chart bundle

Current cache-safe URL (jsDelivr):

```text
https://cdn.jsdelivr.net/gh/77llq/ainvest-vis-cdn@47ad1510fc0101448d8438e9ad947463f372e1b6/aime/vis-skill-assets/standardchart/bundle.umd.min.js
```

For the JSDMirror endpoint, use the same commit-pinned path with `cdn.jsdmirror.com`. The bundle SHA-256 is `bea888aaa314b0859ef2703cc8b36c545fb9dd838230a9deecd535cede572507`.

The `@main` URL keeps its address when the file is updated, but CDN and browser caches can serve older bundles. Use a new commit SHA in consumer URLs for every urgent rollout; adding a query string to a stale JSDMirror `@main` URL did not refresh it in a previous release.

Current bundle: `@datav/standard` version `1.11.7-alpha.2`, built on 2026-10-29 20:01:43 (as recorded in the bundle header).
