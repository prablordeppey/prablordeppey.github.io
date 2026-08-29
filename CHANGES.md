# Personal blog — Browser Extensions table update

Replaces `docs/index.html` (only file changed — same path, drop into repo root).

## Round 1: AliExpress row was misleading
The AliExpress Media Downloader row linked to a Chrome Web Store listing
and a Firefox Add-ons listing that don't actually exist — the Chrome link
even reused the exact same extension ID as the real Alibaba listing
(copy-paste artifact). Since AliExpress isn't published anywhere, that row
now shows an "In Development" badge instead — matching the convention the
YouTube Music Video Downloader row already used for its own unreleased
state.

## Round 2: source links stripped (per your "no source needed")
Removed the two remaining GitHub source-repo links from this table:
- Alibaba Media Downloader row (was linking to
  github.com/theaddonforge/alibaba-media-downloader)
- YouTube Music Video Downloader row (was linking to
  github.com/theaddonforge/youtube-music-downloader)

Both now show plain text instead of a link. The YouTube Channel row's link
was left alone — that's the actual public channel URL, not a source repo.

Also renamed the table's first column header from "Source Codes" (with a
`fa-code` icon) to "Extension" (with `fa-plug`, matching the icon already
used on the section heading above it), since the column no longer holds
source links and the old header/icon no longer described its content.
