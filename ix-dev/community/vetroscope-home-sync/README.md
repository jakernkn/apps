# Vetroscope Home Sync

[Vetroscope Home Sync](https://github.com/rankin-works/vetroscope-home-sync) is the self-hosted sync server for [Vetroscope](https://vetroscope.com), the privacy-first, cross-platform screen-time tracking and productivity app. Run it on your own hardware and point your Vetroscope clients on macOS or Windows at it as an alternative to Vetroscope Cloud. Requires a paid Vetroscope license to connect and sync your data.

Sensitive fields (app names, window titles, project names) are encrypted client-side before upload, so even a compromised server can't read them.

After deploying, open the Vetroscope client, go to **Settings → Sync**, switch to **Home Sync**, and point it at this server. The one-time admin setup code is printed to the container logs on first boot.
