# TytusOS Official Language Index

Official language-pack catalog consumed by **TytusOS → Settings → Languages → Check official packs**.

Raw catalog URL:

```txt
https://raw.githubusercontent.com/traylinx/tytus-os-language-index/main/catalog.json
```

## Available language packs

| Language | Locale | Repo | Raw pack |
|---|---:|---|---|
| Español / Spanish | `es` | https://github.com/traylinx/tytus-os-lang-es | https://raw.githubusercontent.com/traylinx/tytus-os-lang-es/main/tytus-os.es.json |

## How this works

Only packs listed in `catalog.json` are downloadable from the app. Pack URLs must live under:

```txt
https://raw.githubusercontent.com/traylinx/
```

Each entry may include `sha256`; TytusOS verifies it before installing.

## Want to help Tytus speak your language?

Tytus speaks English and Spanish now. Help teach the little OS more languages before it starts inventing Klingon error messages.

To add a language:

1. Create a repo named `tytus-os-lang-<locale>`.
2. Add `tytus-os.<locale>.json` using the same schema as the Spanish pack.
3. Open a PR here adding the pack to `catalog.json` with its SHA-256 checksum.
