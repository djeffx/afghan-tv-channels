# Channel source audit

Checked: 2026-11-09T20:54:09.745862+00:00

Each accepted link returned an HLS manifest and an identifiable media sample from this Mac. This is a point-in-time network check, not a full playback or visual identity test on Fire TV. Broadcaster players or named public catalogues provided identity evidence. Availability can vary by network and region.

Revision 2 adds/replaces sources for Arezo, Zarin, Ariana News and Peace TV, and adds alternatives for Amu and Tamadon. Multiple URLs on one host may still share the same outage risk.

The existing app reads this list on startup, Menu refresh and bounded error recovery. Updating the list does not interrupt current playback. Empty remote entries do not block older built-in or website fallbacks: unresolved channels may still fail or show an incorrect feed until the app itself is updated.

| Channel | Accepted stable URLs | Result |
|---|---:|---|
| Afghanistan International | 1 | Manifest and media sample passed; identity based on named source. |
| Tolo Tv Live Online | 1 | Manifest and media sample passed; identity based on named source. |
| Ariana TV | 1 | Manifest and media sample passed; identity based on named source. |
| Amu TV Live | 2 | Manifest and media sample passed; identity based on named source. |
| Lemar TV | 1 | Manifest and media sample passed; identity based on named source. |
| Tolo News Live | 1 | Manifest and media sample passed; identity based on named source. |
| 1TV Afghanistan | 1 | Manifest and media sample passed; identity based on named source. |
| Shamshad TV Live Online | 1 | Manifest and media sample passed; identity based on named source. |
| Zhwandoon Live TV | 0 | No working public replacement verified. |
| Arezo tv Live | 1 | Manifest and media sample passed; identity based on named source. |
| Tamadon TV Live | 2 | Manifest and media sample passed; identity based on named source. |
| Ariana News TV Live | 1 | Manifest and media sample passed; identity based on named source. |
| VOA Pashto Tv | 1 | VOA media responds; Pashto schedule/language NOT confirmed. Previously displayed Kurdish. |
| Maawj Tv Live | 0 | No working public replacement verified. |
| Begum Tv Live | 0 | Official live player responds, but issues expiring links. Needs an app resolver; no permanent URL published. |
| Khurshid TV | 0 | No working public replacement verified. |
| Chekad Tv Live | 0 | No working public replacement verified. |
| Towheed Tv Live | 0 | Only an expiring, IP-bound link responded. No durable replacement verified. |
| Zarin Tv Live | 1 | Manifest and media sample passed; identity based on named source. |
| Deeyar TV Live | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Sharq TV | 0 | Named Sharq feed failed TLS validation. Other reachable page feed has unconfirmed identity. |
| Dunya Naw TV | 1 | Manifest and media sample passed; identity based on named source. |
| Bahar TV Live | 0 | Known stream returns 404. No working public replacement found. |
| Hasti TV Live | 0 | No working public replacement verified. |
| Faza TV Live | 0 | No working public replacement verified. |
| Maarif TV Live | 0 | Source is RTA education; omitted in keeping with the request to exclude RTA. |
| Afghan TV | 0 | No working public replacement verified. |
| Barya TV Live | 0 | No working public replacement verified. |
| Eslah TV Live | 1 | Manifest and media sample passed; identity based on named source. |
| Ayna TV Live | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Enikass TV Live | 0 | No working public replacement verified. |
| Batur TV Live | 0 | No working public replacement verified. |
| Noor TV Afghanistan Live | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Hewad TV Live | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Zan TV Live | 0 | No working public replacement verified. |
| Kayhan TV Live | 1 | Manifest and media sample passed; identity based on named source. |
| Negaah TV Live Online | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Kabul Tv US Live | 0 | No working public replacement verified. |
| Mitra TV Live | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Asr TV Live | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Jahan Tv Live Afghanistan | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Maiwand TV Live | 0 | No working public replacement verified. |
| Baano TV Live | 0 | No working public replacement verified. |
| Tuti TV Live Online | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Kabul News tv Live | 0 | Original page contains an unrelated or unconfirmed feed; no correct replacement verified. |
| Sada E Afghanistan TV | 0 | No working public replacement verified. |
| Peace TV | 1 | Manifest and media sample passed; identity based on named source. |

17 of 47 entries have a stable URL that passed the media check, including VOA whose language remains unconfirmed. This does not mean all 47 work.

## Accepted links

### Afghanistan International

- https://hls.afintl.com/hls/stream.m3u8

### Tolo Tv Live Online

- https://hrt-stream.movie.af/live/smil:tolotv.smil/playlist.m3u8

### Ariana TV

- https://d3bq19vx8xhpwy.cloudfront.net/live/myStream/playlist.m3u8

### Amu TV Live

- https://jmc-live.ercdn.net/amutv/amutv.m3u8
- https://jmc-live.ercdn.net/amutvbu/amutvbu_720p.m3u8

### Lemar TV

- https://hrt-stream.movie.af/live/smil:lemartv.smil/playlist.m3u8

### Tolo News Live

- https://hrt-stream.movie.af/live/smil:tolonewstv.smil/playlist.m3u8

### 1TV Afghanistan

- https://hrt-stream.movie.af/live/smil:1tv.smil/playlist.m3u8

### Shamshad TV Live Online

- https://hrt-stream.movie.af/live/smil:shamshadtv.smil/playlist.m3u8

### Arezo tv Live

- https://hrt-stream.movie.af/live/smil:arezotv.smil/playlist.m3u8

### Tamadon TV Live

- https://hlst.tamadon.live/hls/stream.m3u8
- https://hls.tamadon.live/hls/stream.m3u8

### Ariana News TV Live

- https://d10rltuy0iweup.cloudfront.net/ATNNEWS/myStream/playlist.m3u8

### VOA Pashto Tv

- https://voa-ingest.akamaized.net/hls/live/2033781/tvmc02/playlist.m3u8

### Zarin Tv Live

- https://rpn3.bozztv.com/cus01/esh-zarintv-push/esh-zarintv-push/index.m3u8

### Dunya Naw TV

- https://dunyanhls.wns.live/hls/stream.m3u8

### Eslah TV Live

- https://eslahtvhls.wns.live/hls/stream.m3u8

### Kayhan TV Live

- https://playout395.livestreamingcdn.com/live/Stream1/playlist.m3u8

### Peace TV

- https://dzkyvlfyge.erbvr.com/PeaceTvEnglish/index.m3u8


## Maintaining the list

Edit channels.json, keep page identifiers stable, increment revision and update updatedAt. Never commit credentials or expiring signed links. The app validates the complete list and keeps its cached copy if a download or validation fails. This repository hosts playback URLs, not video.
