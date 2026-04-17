# Magic Plugins — Releases

Public host for Magic Plugins installer artifacts (`.pkg`, `.exe`) and the
`manifest.json` that the plugins read to detect newer versions.

No source code lives here. Source repositories are private.

## `manifest.json`

Consumed by each plugin's in-app update check. One top-level key per plugin;
each entry carries the latest version, release date, platform download URLs,
and a marketing/info URL.

```
https://raw.githubusercontent.com/Magic-Plugins/releases/main/manifest.json
```

## Release tag convention

```
magic-vocals-v1.5.1
pitch-tool-v1.0.0
```

## Release workflow

See `directives/10_auto_update.md` in the `magicVocals` source repository.

## Support policy

Each plugin has one supported version at a time (the "Latest" release).

Older versions are retained permanently as archives for customers with
legacy projects, but are **not maintained**:

- No bug fixes
- No OS / DAW compatibility updates
- No user support

If a customer opens a support request about an archived version, we
provide the download link and ask them to upgrade to the Latest release
for any further assistance.
