# Zed Fonts
**Zed Mono** & **Zed Sans** are custom builds of [Iosevka](https://github.com/be5invis/Iosevka) licensed under the SIL Open Font License, Version 1.1.

They are built for use in [Zed](https://zed.dev/). **Zed Sans** uses a quasi-proportional spacing to allow the font to still feel monospace while not having such wide gaps in a UI setting.

You can read the license here: [LICENSE.md](https://github.com/zed-industries/zed-fonts/blob/main/LICENSE.md).

## Building Zed Mono

**Warning:** This is a pretty heavy operation. Don't be surprised to see your CPU jump to 100% for minutes to hours depending on your machine.

Custom configurations are set up in `private-build-plans.toml`.

To build, run: `build.sh`

Output will be in `/dist`
