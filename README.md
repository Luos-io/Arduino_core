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
