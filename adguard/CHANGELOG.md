[Full Changelog][changelog]

⚠️ **If you see `This add-on is not available on your system.`; please continue reading...**

This is a release ships with AdGuard Home v0.99.0!

<https://github.com/AdguardTeam/AdGuardHome/releases/tag/v0.99.0>

There are some caveats with this release:

- The add-on **requires** Home Assistant **>= 0.101.0b0** (0.101.0 beta or newer). **You won't be able to update or install this version if you don't meet this requirement.**
  In that case, you will get a `This add-on is not available on your system.` message.
- Home Assistant >= 0.100.0b0 requires at least AdGuard Home v0.99.0 (this release) for the integration to work.
- AdGuard displays a version check error, this bug is expected to be fixed in AdGuard 0.99.1, however, it does not influence the working of AdGuard Home.

### 🔨 Changes

- :arrow_up: Upgrade AdGuard Home to v0.99.0 (#35)
- :arrow_up: Upgrades add-on base image to v5.0.1
- :heavy_plus_sign: Require Home Assistant 0.101.0b0 or newer

[changelog]: https://github.com/hassio-addons/addon-adguard-home/compare/v2.1.0...v2.2.0

Questions? Join our Discord server! https://discord.me/hassioaddons
Enjoying my add-ons? Consider supporting my work: https://patreon.com/frenck