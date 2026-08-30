# Personal blog — index.html changes

Replaces `docs/index.html` (only file changed — same path, drop into repo root).

## Round 3: new "Dataset Foundry" entry added
Added a new card under **Web Platforms & Sites** (`item-6`, after the
existing Timothy Azirigo entry) for Dataset Foundry, based on the actual
live site content at https://datasetfoundry.github.io/:

- Live Site link, with a "Domain pending" badge — same badge/wording
  already used for the Renoval Solutions entry, since you mentioned a
  custom domain hasn't been purchased yet.
- Role: Founder & Lead Developer (matches the founder attribution on the
  live site).
- Stack: Django REST Framework backend, Astro + TypeScript frontend —
  worded so it doesn't imply the backend itself is on GitHub Pages, just
  the frontend.
- Target Users and Features summarized from the site's own copy (synthetic
  data platform, four live line families — Insurance, Finance, Health,
  Agriculture — deterministic generation, manifest/checksum/citation block
  on every download).

Placed under Web Platforms rather than "Published Software Packages"
(where the browser extensions table lives) since this is a hosted web
platform, not an installable package or extension — matching how 2KAP,
Renoval, Yenko WiFi, Tim Supply, and the Timothy Azirigo site are already
categorized there.

## Round 1: AliExpress row was misleading
The AliExpress Media Downloader row previously linked to a Chrome Web
Store listing and a Firefox Add-ons listing that don't actually exist —
the Chrome link even reused the exact same extension ID as the real
Alibaba listing (copy-paste artifact). Since AliExpress isn't published
anywhere, that row now shows an "In Development" badge instead — matching
the convention the YouTube Music Video Downloader row already used for
its own unreleased state.

## Round 2: source links stripped ("no source needed")
Removed the two remaining GitHub source-repo links from the Browser
Extensions table:
- Alibaba Media Downloader row
- YouTube Music Video Downloader row

Both now show plain text instead of a link. The YouTube Channel row's
link was left alone — that's the actual public channel URL, not a source
repo. Renamed the table's first column header from "Source Codes"
(`fa-code` icon) to "Extension" (`fa-plug`, matching the section heading's
own icon), since the column no longer holds source links.
