- Layout config with: https://nickcoutsos.github.io/keymap-editor (use it to modify keymap)
- Firmaware Zephyr 3.5


```note

LY0 Dvorak
                KEY POSITIONS 3 x 5
  ╭─────────────────────╮ ╭─────────────────────╮
  │  ;   ,   .   P   Y  │ │  P   G   C   R   L  │
  │  A   O   E   U   I  │ │  D   H   T   N   S  │
  │  '   Q   J   K   X  │ │  B   M   W   V   Z  │
  ╰───────╮ Esc Tab Spc │ │ Cps Ent Bsp ╭───────╯
          ╰─────────────╯ ╰─────────────╯

Hold
  ╭─────────────────────╮ ╭─────────────────────╮
  │  -   -  LY5 LY6  -  │ │  -   -  LY6  -   -  │
  │  -   -   -   -   -  │ │  -  ly6 ly6  -   -  │
  │ Shf ly5 LY2 LY7  -  │ │  -   -  LY3 LY7 Shf │
  ╰───────╮ [T]  -  LY6 │ │ ly1  -   -  ╭───────╯
          ╰─────────────╯ ╰─────────────╯

[T] Toggle = 🖱 Mouse BLE
  ╭─────────────────────╮ ╭─────────────────────╮
  │  -   -  LY5 LY6  -  │ │  -   ⮴  ⮵   -   -  │
  │  ⮈  ⮋   ⮉  ⮊   .  │ │  -  ls  ly6  -   -  │
  │ Shf Ctl  -  Spr Alt │ │  -   -  LY3 LY7 Shf │
  ╰───────╮ [T]  -   -  │ │  -  -   -  ╭───────╯
          ╰─────────────╯ ╰─────────────╯

*note: small (ly5, ly6) is temporary finger trigger or not
        [T] = Toggle [doube tab]

lY1        = Bt Connect + Reset | F1 - 12 
LY2        = Helper L [ctrl + shift + mod]
LY3        = Helper R [ctrl + shift + mod]
LY4        = Symbol [R] + @ [L]
LY5        = Primary Number [L] + Symbol && mod shortcut
LY6 | [T]  = Mouse && Control arrow + page
LY7        = Macro
```



```sh
# log : Xorg

$ ...xxx Keyboard: client bug: event processing lagging behind by 'xx' ms, your system is too slow
$ keyboard: always repert core events
```
