# Egg Character Generator

A Codex skill that converts a user-provided portrait or pet photo into a soft
3D egg-shaped character. It uses one structural reference and one paired
before/after example to preserve identity while keeping the egg silhouette.

This is an independent project and is not affiliated with, endorsed by, or
sponsored by any third-party product or company.

## Install

Copy this folder into your Codex skills directory, then invoke:

```text
$generate-egg-character
```

Provide one portrait or pet photo when invoking the skill. The photo is sent
to the configured image-generation provider for processing. It must not be
added to this repository, and the provider's privacy and data-use terms apply.

## Privacy

The repository intentionally contains no user identity photos. The skill does
not intentionally copy runtime identity photos into its folder, examples, or
version history. Common input and output directories are excluded through
`.gitignore`. Before every commit, review `git status` and confirm that no
private photo is staged.

## Licensing

The skill instructions and metadata are available under the MIT License. The
reference images have separate terms in `ASSET_LICENSE.md`.
