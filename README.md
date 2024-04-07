## ZMK-Config

Config for my keyboards running ZMK. Currently only Lily58, running nicenanov2 board.

### Customize keymap

Updating the keymap are most easily done using https://nickcoutsos.github.io/keymap-editor/.

Keymaps are built using GitHub Actions. Simply edit `.keymap` file and push.
GH action will run and build the firmware.

* Push updated `.keymap`.
* Download build artifact from action.
* Connect keyboard with USB
* Double click reset to enter flash
* Copy build artifact to root of device
* Done!


Detailed instructions here https://zmk.dev/docs/user-setup
