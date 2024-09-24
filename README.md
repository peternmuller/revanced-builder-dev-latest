#### ⚠️ Do not download APKs or modules from random websites you find on Google, as they may be dangerous and because providers impersonate ReVanced/ReVanced Extended. Please build your application from official sources or use open source builders like this one.

# Welcome to my ReVanced Builder!
[![CI](https://github.com/peternmuller/revanced-builder-dev-latest-dev-latest/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/peternmuller/revanced-builder-dev-latest/actions/workflows/ci.yml)
[![GitHub License](https://img.shields.io/github/license/peternmuller/revanced-builder-dev-latest-dev-latest?logo=gnu&label=License&link=https%3A%2F%2Fgithub.com%2Fpeternmuller%2Frevanced-builder-dev-latest%2Fblob%2Fmain%2FLICENSE)](https://github.com/peternmuller/revanced-builder-dev-latest/blob/main/LICENSE)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/peternmuller/revanced-builder-dev-latest/total?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48cGF0aCBkPSJNNC43NSAxNy4yNWEuNzUuNzUgMCAwIDEgLjc1Ljc1djIuMjVjMCAuMTM4LjExMi4yNS4yNS4yNWgxMi41YS4yNS4yNSAwIDAgMCAuMjUtLjI1VjE4YS43NS43NSAwIDAgMSAxLjUgMHYyLjI1QTEuNzUgMS43NSAwIDAgMSAxOC4yNSAyMkg1Ljc1QTEuNzUgMS43NSAwIDAgMSA0IDIwLjI1VjE4YS43NS43NSAwIDAgMSAuNzUtLjc1WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjxwYXRoIGQ9Ik01LjIyIDkuOTdhLjc0OS43NDkgMCAwIDEgMS4wNiAwbDQuOTcgNC45NjlWMi43NWEuNzUuNzUgMCAwIDEgMS41IDB2MTIuMTg5bDQuOTctNC45NjlhLjc0OS43NDkgMCAxIDEgMS4wNiAxLjA2bC02LjI1IDYuMjVhLjc0OS43NDkgMCAwIDEtMS4wNiAwbC02LjI1LTYuMjVhLjc0OS43NDkgMCAwIDEgMC0xLjA2WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjwvc3ZnPg==&label=Downloads&link=https%3A%2F%2Fgithub.com%2Fpeternmuller%2Frevanced-builder-dev-latest%2Freleases)](https://github.com/peternmuller/revanced-builder-dev-latest/releases)

This ReVanced Builder creates both APKs and [Magisk](https://github.com/topjohnwu/Magisk)/[KernelSU](https://github.com/tiann/KernelSU) modules for [ReVanced](https://github.com/ReVanced) and [ReVanced Extended](https://github.com/inotia00/revanced-patches) versions of YouTube and YouTube Music.

#### **Get the latest CI release [here](https://github.com/peternmuller/revanced-builder-dev-latest/releases/latest)!**

## Installation
### Non-root users
- Install the [ReVanced GmsCore app](https://github.com/ReVanced/GmsCore/releases/latest).
- Download the APK files you want to install from the [releases page](https://github.com/peternmuller/revanced-builder-dev-latest/releases/latest).
- (Optional) Import [one of my custom settings file](https://github.com/peternmuller/revanced-builder-dev-latest/tree/main/custom-settings) in your application. [*How to do this?*](https://github.com/peternmuller/revanced-builder-dev-latest/tree/main/custom-settings)
- Enjoy!
### Root users
- Download the ZIP files you want to flash from the [releases page](https://github.com/peternmuller/revanced-builder-dev-latest/releases/latest).
- (Optional) Import [one of my custom settings file](https://github.com/peternmuller/revanced-builder-dev-latest/tree/main/custom-settings) in your application. [*How to do this?*](https://github.com/peternmuller/revanced-builder-dev-latest/tree/main/custom-settings)
- (Optional) Use [zygisk-detach](https://github.com/j-hc/zygisk-detach) to detach YouTube and YouTube Music from the Play Store.
- Enjoy!

## Easily update ReVanced apps with Obtainium
You can easily update the ReVanced apps from this builder by using [Obtainium](https://github.com/ImranR98/Obtainium) which allows you to install and update apps directly from their releases pages, and receive notifications when new releases are made available.

#### Here is a quick tutorial on how to add them to Obtainium:

<img width="2160" alt="obtainium_quick_tutorial" src="https://github.com/user-attachments/assets/3f0af16e-328e-4831-99c5-9253192403c7">

> [!NOTE]
> In step 5, you need to enter the regular expression that corresponds to the application you want to install:
> - YouTube ReVanced Extended: `youtube-revanced-extended`
> - YouTube Music ReVanced Extended: `yt-music-revanced-extended`
> - YouTube ReVanced anddea: `youtube-revanced-anddea`
> - YouTube Music ReVanced anddea: `yt-music-revanced-anddea`

## Import custom settings in ReVanced applications
I personally like my YouTube and YouTube Music applications to be as close as possible to the original look, but less cluttered, easier and less annoying to use. If this is also the case for you, I highly recommend importing [my custom settings files](https://github.com/peternmuller/revanced-builder-dev-latest/tree/main/custom-settings).

**To do this, go to YouTube Settings &rarr; ReVanced (or ReVanced Extended) &rarr; Miscellaneous (or Advanced Settings for YouTube Music) &rarr; Import&nbsp;/&nbsp;Export settings.**

## Building Locally
### On Termux
```bash
bash <(curl -sSf https://raw.githubusercontent.com/peternmuller/revanced-builder-dev-latest/main/build-termux.sh)
```
### On Desktop
```bash
git clone https://github.com/peternmuller/revanced-builder-dev-latest
cd revanced-builder-dev-latest
./build.sh
```

## Credits
- [j-hc](https://github.com/j-hc) for creating this amazing builder.
- [Kevinr99089](https://github.com/kevinr99089) for providing assistance with the builder.
- [KitsunedFox](https://github.com/KitsunedFox) for the idea of the Obtainium tutorial.
- And of course, the [ReVanced](https://github.com/ReVanced) team, [inotia00](https://github.com/inotia00) and [anddea](https://github.com/anddea) for their work on the ReVanced apps!

## License
    Copyright (C) 2024  Peter Noël Muller

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <https://www.gnu.org/licenses/>.