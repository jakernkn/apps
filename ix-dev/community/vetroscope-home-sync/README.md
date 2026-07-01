# Vetroscope Home Sync

[Vetroscope Home Sync](https://github.com/rankin-works/vetroscope-home-sync) is the self-hosted sync server for [Vetroscope](https://vetroscope.com), the privacy-first, cross-platform screen-time tracking and productivity app. Run it on your own hardware and point your Vetroscope clients at it as an alternative to Vetroscope Cloud.

Sensitive fields (app names, window titles, project names) are encrypted client-side before upload, so even a compromised server can't read them.

After deploying, open the Vetroscope client, go to **Settings → Sync**, switch to **Home Sync**, and point it at this server. The one-time admin setup code is printed to the container logs on first boot.
