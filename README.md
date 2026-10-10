# tinyland-credentials-helper (retired)

**Retired 2026-10-09. This repository is archived and receives no further changes.**

`@tummycrypt/tinyland-credentials-helper` provided credential onboarding helpers
(credential generation, download responses, email HTML and secure share links).
No live app or Bazel registry module depends on it, so it is retired without a
replacement module (estate uplift rulings RU2/RU7).

- Bazel module: `tummycrypt_tinyland_credentials_helper` in
  [xoxd-ai/bazel-registry](https://github.com/xoxd-ai/bazel-registry) is marked
  deprecated. Version 0.2.2 stays resolvable; nothing is yanked.
- npm: no further versions are published (RU8). Existing npmjs and GitHub
  Packages versions stay available and are being marked deprecated.
- Credential and admission flows now live in
  [tinyland-auth](https://github.com/xoxd-ai/tinyland-auth) and
  [tinyland-invitation](https://github.com/xoxd-ai/tinyland-invitation).

The source and tags (v0.1.0, v0.2.0, v0.2.2) are kept for history. Nothing was
deleted.
