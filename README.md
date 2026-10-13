# Public live playlists

This repository hosts generated playlists and a static landing page only.
Generator scripts, source catalogs and tests are maintained separately in a
private repository. No self-hosted runners belong to this public repository.
The small Pages deployment workflow runs exclusively on GitHub-hosted runners.

## APTV subscription URLs

- Website: https://charlesdiraviam.github.io/iptv-yt/
- All channels: https://charlesdiraviam.github.io/iptv-yt/all_live.m3u
- YouTube channels: https://charlesdiraviam.github.io/iptv-yt/all_youtube_live.m3u
- Tamil channels: https://charlesdiraviam.github.io/iptv-yt/tamil_live.m3u
- Direct broadcaster feeds: https://charlesdiraviam.github.io/iptv-yt/tamil_broadcaster_live.m3u
- Status: https://charlesdiraviam.github.io/iptv-yt/status.json

The website links all ten regional and combined playlists. Add a playlist as an
APTV subscription and manually refresh before use. Car video viewing is for parked
use only.

## Refresh and playback

The private generator is configured for a best-effort two-hour refresh using a
trusted home runner. Until that runner and its publishing credential are configured,
this repository contains only the bootstrap output. Check the published UTC
timestamp; a successful Pages deployment is not proof of a new extraction run.

GitHub Pages serves only playlist URLs, not video. Your player fetches media directly
from the provider. YouTube links expire and may be restricted to the generating IP,
so cellular playback must be tested separately. Published signed URLs can reveal
the generator's public IP. No credentials or authentication cookies are published.

## Repository history

The public main history was replaced, with owner approval, by a hosting-only history.
Earlier public generator versions may remain available via cached commits, forks,
logs or other copies. This change does not make previously published code secret.

Only generated content in `site/` is deployed; this README and the deployment
workflow are not part of the website. Pages source must remain **GitHub Actions**.