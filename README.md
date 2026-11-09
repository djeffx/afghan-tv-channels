# Afghan TV channel sources

Public playback-source list for the standalone Afghan TV app. Video streams directly from the listed hosts; this repository does not host video.

`channels.json` contains a schema version, increasing revision number and channel records keyed by their original page URL. Stream order determines fallback preference. URLs are public sources, not a guarantee of availability. Bahar currently has no verified working replacement.

To update sources, edit the appropriate channel's streams, increment `revision`, update `updatedAt` and commit. Keep page identifiers stable so favourites stay matched. Never add passwords, API keys, private URLs or expiring website-issued signatures. The app integration must validate the whole list before replacing its cached copy and retain the previous list when a download or validation fails.
