# BETA - Community Hass.io Add-ons for Home Assistant

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitLab CI][gitlabci-shield]][gitlabci]
![Awesome][awesome-shield]

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

## WARNING! THIS IS A BETA REPOSITORY

This Hass.io Add-ons repository contains beta releases of add-ons.

- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.

If you are more interested in stable releases of our add-ons:

<https://github.com/hassio-addons/repository>

## Installation

Adding this add-ons repository to your Hass.io Home Assistant instance is
pretty easy. Follow [the official instructions][third-party-addons] on the
website of Home Assistant, and use the following URL:

```txt
https://github.com/hassio-addons/repository-beta
```

## Add-ons provided by this repository

### &#10003; [AirCast][addon-aircast]

![Latest Version][aircast-version-shield]
![Supports armhf Architecture][aircast-armhf-shield]
![Supports aarch64 Architecture][aircast-aarch64-shield]
![Supports amd64 Architecture][aircast-amd64-shield]
![Supports i386 Architecture][aircast-i386-shield]
![Docker Pulls][aircast-pulls-shield]

AirPlay capabilities for your Chromecast devices.

[:books: AirCast add-on documentation][addon-doc-aircast]

### &#10003; [AirSonos][addon-airsonos]

![Latest Version][airsonos-version-shield]
![Supports armhf Architecture][airsonos-armhf-shield]
![Supports aarch64 Architecture][airsonos-aarch64-shield]
![Supports amd64 Architecture][airsonos-amd64-shield]
![Supports i386 Architecture][airsonos-i386-shield]
![Docker Pulls][airsonos-pulls-shield]

AirPlay capabilities for your Sonos (and UPnP) devices.

[:books: AirSonos add-on documentation][addon-doc-airsonos]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

The beta add-ons will also have an additional beta marker, unless, the
stable release is newer, in that case, the stable release is published
in this channel.

## Support

Got questions?

You have several options to get them answered:

- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: AirCast][aircast-issue]
- [Open an issue for the add-on: AirSonos][airsonos-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Adding a new add-on

Have you created an add-on that you want to list in the Community Repository?
Contact [Franck Nijhof][frenck]:

- Drop him an email: frenck@addons.community
- Chat with him on [Discord Chat][discord]: Frenck#4484 (@frenck)
- Message him via the forums: [frenck][forum-frenck]

He will set up a GitHub repository and all the other plumbing,
and of course, give you developer access to your contribution.

## License

MIT License

Copyright (c) 2018 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-aircast]: https://github.com/hassio-addons/addon-aircast/tree/v0.3.0
[addon-doc-aircast]: https://github.com/hassio-addons/addon-aircast/blob/v0.3.0/README.md
[aircast-issue]: https://github.com/hassio-addons/addon-aircast/issues
[aircast-version-shield]: https://img.shields.io/badge/version-v0.3.0-blue.svg
[aircast-pulls-shield]: https://img.shields.io/docker/pulls/hassioaddons/aircast-armhf.svg
[aircast-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[aircast-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[aircast-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[aircast-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-airsonos]: https://github.com/hassio-addons/addon-airsonos/tree/v0.3.1
[addon-doc-airsonos]: https://github.com/hassio-addons/addon-airsonos/blob/v0.3.1/README.md
[airsonos-issue]: https://github.com/hassio-addons/addon-airsonos/issues
[airsonos-version-shield]: https://img.shields.io/badge/version-v0.3.1-blue.svg
[airsonos-pulls-shield]: https://img.shields.io/docker/pulls/hassioaddons/airsonos-armhf.svg
[airsonos-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[airsonos-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[airsonos-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[airsonos-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[awesome-shield]: https://img.shields.io/badge/awesome%3F-yes-brightgreen.svg
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg
[discord]: https://discord.gg/c5DvZ4e
[forum-frenck]: https://community.home-assistant.io/u/frenck/?u=frenck
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io?u=frenck
[frenck]: https://github.com/frenck
[gitlabci-shield]: https://gitlab.com/hassio-addons/repository-beta/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/hassio-addons/repository-beta/pipelines
[issue]: https://github.com/hassio-addons/repository-beta/issues
[license-shield]: https://img.shields.io/github/license/hassio-addons/repository-beta.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2018.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-development-yellowgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html
[third-party-addons]: https://home-assistant.io/hassio/installing_third_party_addons/