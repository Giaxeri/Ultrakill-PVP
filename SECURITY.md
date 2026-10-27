# Security

## Supported versions

Only the latest release gets fixes. Everyone in a lobby needs the same version anyway, so please update before
reporting.

## Reporting a problem

Please report it privately:

- On GitHub, use "Report a vulnerability" in the Security tab of
  [Giaxeri/Ultrakill-PVP](https://github.com/Giaxeri/Ultrakill-PVP/security), if it's there.
- Or send a DM to Giaxeri on the Discord: https://discord.gg/MtmMgxhCC

Say which version and build (GitHub or Thunderstore) you have and how to reproduce it. Please don't post exploits or
cheats in public channels or issues until there's a fix.

## What the mod does to protect players

- The in-game UPDATE only installs a release whose manifest is signed (RSA-3072) and matches the files.
  The Thunderstore version has no updater at all.
- Packets from other players have size and rate limits, and anything malformed is dropped.
- Damage from other players is checked against each weapon's limits before it counts.
- Traffic goes through Epic's or Steam's relays, so other players never see your IP address.
- No analytics and no player counting.
