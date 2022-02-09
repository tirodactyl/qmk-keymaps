# Keymaps to share
I found this cool new idea for having separate repos for keymaps rather than dealing with a fork of QMK.

# Future
I intend to put together a build system so that I don't have to fight QMK every time I decide to build a new keyboard.

# Setting up QMK

```
git clone https://github.com/qmk/qmk_firmware.git
cd qmk_firmware
util/qmk_install.sh
```

# Using these keymaps
From the qmk root dir:

```
cp <pathtocustomkeymaps>/<keyboardname> keyboards/<keyboardname>/tirodactyl

make <keyboardname>:tirodactyl
```
