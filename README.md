<a href="https://luos.io"><img src="https://uploads-ssl.webflow.com/601a78a2b5d030260a40b7ad/603e0cc45afbb50963aa85f2_Gif%20noir%20rect.gif" alt="Luos logo" title="Luos" align="right" height="100" /></a>

![](https://github.com/Luos-io/luos_engine/actions/workflows/build.yml/badge.svg)
[![](https://img.shields.io/github/license/Luos-io/Arduino_core)](https://github.com/Luos-io/luos_engine/blob/master/LICENSE)
[![](https://img.shields.io/badge/Luos-Documentation-34A3B4)](https://www.luos.io/docs)
[![](http://certified.luos.io)](https://www.luos.io)
[![PlatformIO Registry](https://badges.registry.platformio.org/packages/luos/library/luos_engine.svg)](https://registry.platformio.org/libraries/luos/luos_engine)

[![](https://img.shields.io/discord/902486791658041364?label=Discord&logo=discord&style=social)](http://bit.ly/JoinLuosDiscord)
[![](https://img.shields.io/reddit/subreddit-subscribers/Luos?style=social)](https://www.reddit.com/r/Luos)

# Luos Arduino core
Adapted versions of Arduino core allowing to support Luos.

# How to use with Arduino IDE

Copy and paste the following URL into the File > Preferences > "Additional Boards Manager" textbox.

```
https://raw.githubusercontent.com/Luos-io/Arduino_core/main/package_luos_index.json
```

Now you can install the Luos adapted Arduino SAMD Library !

Boards > "Add board definition" > Search for "Luos" > Install "Luos adapted Arduino SAMD (32-bits ARM Cortex-M0+) Boards"

Make sure to also install the Arduino SAMD Library at the same time (because arduino seems to install some drivers on windows).

Boards > "Add board definition" > Search for "SAMD" > Install Arduino SAMD Library

## Don't hesitate to read [our documentation](https://www.luos.io), or to post your questions/issues on the [Luos' Discord server](https://discord.gg/luos). :books:
