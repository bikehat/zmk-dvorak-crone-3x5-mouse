Fw Zephyr 3.5
- This config was built with: https://nickcoutsos.github.io/keymap-editor (use it to modify keymap)

```sh
                KEY POSITIONS 3 x 5
  ╭─────────────────────╮ ╭─────────────────────╮
  │  ;   ,   .   P   Y  │ │  P   G   C   R   L  │
  │  A   O   E   U   I  │ │  D   H   T   N   S  │
  │  '   Q   J   K   X  │ │  B   M   W   V   Z  │
  ╰───────╮ Esc Tab Spc │ │ Cps Ent Bsp ╭───────╯
          ╰─────────────╯ ╰─────────────╯ 
```

```bash
# log date 250725 : Xorg

$ ...xxx Keyboard: client bug: event processing lagging behind by 'xx' ms, your system is too slow

$ keyboard: always repert core events
$ Option "Device" xxxx
```

only personal opinion | reduce pain BLE in your system
edit zmk file ``config/corne.conf``

```bash
# https://zmk.dev/docs/keymaps/behaviors/mouse-emulation
# warning: REFRESHING THE HID DESCRIPTOR
#
# https://zmk.dev/docs/features/bluetooth#refreshing-the-hid-descriptor
# https://zmk.dev/docs/config/system#hid
CONFIG_ZMK_HID_INDICATORS=n
# change value [1] / [2], or extearm [0] depend in your habit HID
CONFIG_ZMK_HID_CONSUMER_REPORT_SIZE=0
CONFIG_ZMK_HID_SEPARATE_MOD_RELEASE_REPORT=n

# MOUSE
CONFIG_ZMK_POINTING=y
```
