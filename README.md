# AInvest visualization CDN assets

Public assets for AInvest visualization integrations.

## Standard Chart bundle

Current cache-safe URL (jsDelivr):

```text
https://cdn.jsdelivr.net/gh/77llq/ainvest-vis-cdn@23e64a3e61e0162f866e4059dfb78bea5382f877/aime/vis-skill-assets/standardchart/bundle.umd.min.js
```

For the JSDMirror endpoint, use the same commit-pinned path with `cdn.jsdmirror.com`. Both pinned URLs have been checked against the build SHA-256 `06244f6d874499dafb75deb496adaa69bfaa46fe43d35c49ef206690be1eeca1`.

The `@main` URL keeps its address when the file is updated, but CDN and browser caches can serve older bundles. Use a new commit SHA in consumer URLs for every urgent rollout; adding a query string to a stale JSDMirror `@main` URL did not refresh it in this release.

Current bundle: `@datav/standard` version `1.11.7-alpha.2`, built from standard-chart commit `09bbd66da` on 2026-10-23.
