# KSHomeLab Kometa Config

Custom Kometa (Plex Meta Manager) configuration, overlays, and collections.

## Directory Structure

```
Kometa/
├── overlays/           # Overlay images (.png)
│   ├── resolution/     # 4K, 1080p, 720p, etc.
│   ├── audio/          # Dolby Atmos, DTS-X, etc.
│   ├── streaming/      # Netflix, Disney+, etc.
│   ├── status/         # Airing, Returning, Ended, Cancelled
│   ├── network/        # TV network logos
│   ├── studio/         # Movie studio logos
│   ├── ribbons/        # Award ribbons, trending, ratings
│   └── custom/         # Custom overlays
├── collections/        # Collection YAML configs
├── templates/          # Design templates
│   ├── photoshop/      # PSD source files
│   └── overlays/       # Overlay templates
├── posters/            # Custom poster artwork
├── scripts/            # Automation scripts
└── docs/               # Documentation
```

## Usage

Reference overlays in Kometa config using raw GitHub URLs:

```yaml
url: https://raw.githubusercontent.com/KSHomeLab/Kometa/main/overlays/resolution/4k.png
```

## Overlay Naming Conventions

| Type | Examples |
|------|----------|
| Resolution | `4k.png`, `1080p.png`, `720p.png`, `480p.png` |
| Audio | `dolby-atmos.png`, `dts-x.png`, `truehd.png` |
| Streaming | `netflix.png`, `disney.png`, `hulu.png`, `appletv.png` |
| Status | `airing.png`, `returning.png`, `ended.png`, `cancelled.png` |
| Ribbons | `imdb-top.png`, `trending.png`, `oscar.png` |

## Resources

- [Kometa Wiki](https://kometa.wiki/)
- [s0len's meta-manager-config](https://github.com/s0len/meta-manager-config) - Inspiration
