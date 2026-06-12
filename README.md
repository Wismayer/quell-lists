# quell-lists

Compiled filter lists for [Quell](https://github.com/sebastianwismayer/Quell), an ad and
tracker blocker for Safari on iOS and macOS. This repository is published automatically;
the app fetches `manifest.json` (Safari content blocker shards) and `prefilter.json`
(URL-filter Bloom prefilter) from its GitHub Pages site.

These files are machine-converted from the following upstream filter lists, and are
republished here in compiled form in accordance with their licenses:

| Source | License |
| --- | --- |
| [EasyList](https://easylist.to/) | [GPLv3](https://easylist.to/pages/licence.html) / CC BY-SA 3.0 (dual) |
| [EasyPrivacy](https://easylist.to/) | GPLv3 / CC BY-SA 3.0 (dual) |
| [EasyList Cookie List (fanboy-cookiemonster)](https://secure.fanboy.co.nz/) | GPLv3 / CC BY-SA 3.0 (dual) |

Conversion to Safari content-blocker JSON uses
[AdGuard SafariConverterLib](https://github.com/AdguardTeam/SafariConverterLib) (GPLv3)
as part of the build tooling.

The compiled lists in this repository are accordingly available under
**GPLv3 / CC BY-SA 3.0**. All credit for the filter rules belongs to the upstream
list maintainers.
