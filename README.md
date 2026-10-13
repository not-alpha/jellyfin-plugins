# jellyfin-plugins

A personal Jellyfin plugin catalogue with pinned versions.

Add this address in Jellyfin under Dashboard → Plugins → Manage Repositories:

```
https://raw.githubusercontent.com/not-alpha/jellyfin-plugins/main/manifest.json
```

## What it lists

| Plugin | Version | Built for | File |
|---|---|---|---|
| JavaScript Injector | 4.0.0.0 | Jellyfin 12 | [release in the fork](https://github.com/not-alpha/Jellyfin-JavaScript-Injector/releases/tag/4.0.0.0) |

The file is an unmodified copy of the upstream release by
[n00bcodr](https://github.com/n00bcodr/Jellyfin-JavaScript-Injector) (GPL-3.0);
its MD5 checksum matches the upstream catalogue. The source is in the fork at
the `4.0.0.0` tag.

## Updating

A plugin only changes when `manifest.json` here is edited: add a new entry to
`versions` with the new file's address and MD5 checksum.
