# Custom Home Assistant Community Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

In general, there is no need to install this repository on your
Home Assistant instance. It is activated and added by Home Assistant
by default.

However, if the repository is missing on your setup, adding this add-ons
repository to your Home Assistant instance is pretty easy. In the
Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/sirfixalotgk/ha-repository
```

## Add-ons provided by this repository

### &#10003; [Z-Wave JS UI Secondary][addon-zwave-js-ui]

![Latest Version][zwave-js-ui-version-shield]
![Supports armhf Architecture][zwave-js-ui-armhf-shield]
![Supports armv7 Architecture][zwave-js-ui-armv7-shield]
![Supports aarch64 Architecture][zwave-js-ui-aarch64-shield]
![Supports amd64 Architecture][zwave-js-ui-amd64-shield]
![Supports i386 Architecture][zwave-js-ui-i386-shield]

Fully configurable Z-Wave JS gateway and control panel

[:books: Z-Wave JS UI add-on documentation][addon-doc-zwave-js-ui]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You have several options to get them answered:

- The Home Assistant Community Add-ons [Discord Chat Server][discord]
- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord-ha].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Z-Wave JS UI][zwave-js-ui-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Adding a new add-on

We are currently not accepting third party add-ons to this repository.

For questions, please contact [Franck Nijhof][frenck]:

- Drop him an email: frenck@addons.community
- Chat with him on [Discord Chat][discord]
- Message him via the forums: [frenck][forum-frenck]

## License

MIT License

Copyright (c) 2017-2024 Franck Nijhof

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

[addon-zwave-js-ui]: https://github.com/hassio-addons/addon-zwave-js-ui/tree/v4.6.0
[addon-doc-zwave-js-ui]: https://github.com/hassio-addons/addon-zwave-js-ui/blob/v4.6.0/README.md
[zwave-js-ui-issue]: https://github.com/hassio-addons/addon-zwave-js-ui/issues
[zwave-js-ui-version-shield]: https://img.shields.io/badge/version-v4.6.0-blue.svg
[zwave-js-ui-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[zwave-js-ui-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[zwave-js-ui-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[zwave-js-ui-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[zwave-js-ui-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[awesome-shield]: https://img.shields.io/badge/awesome%3F-yes-brightgreen.svg
[awesome]: https://awesome-ha.com
[discord-ha]: https://discord.gg/c5DvZ4e
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[discord]: https://discord.me/hassioaddons
[forum-frenck]: https://community.home-assistant.io/u/frenck/?u=frenck
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io?u=frenck
[frenck]: https://github.com/frenck
[gitlabci-shield]: https://gitlab.com/hassio-addons/repository/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/hassio-addons/repository/pipelines
[issue]: https://github.com/hassio-addons/repository/issues
[license-shield]: https://img.shields.io/github/license/hassio-addons/repository.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2024.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html
