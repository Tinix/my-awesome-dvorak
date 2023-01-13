# My Awesome Dvorak us keyboard layout
 This is my custom programmer dvorak for javascript layout, its based in programmer Dvorak by Roland Kaufman.

## Overview

 ISO
 ┌─────┐
 │ 2 4 │   2 = Shift,  4 = AltGr + Shift
 │ 1 3 │   1 = Normal, 3 = AltGr
 └─────┘
 ┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
 │ %   │ $   │ 7   │ 5   │ 3   │ 1   │ 9   │ 0   │ 2   │ 4   │ 6   │ 8   │ ´ ˇ ┃ ⌫ Back  ┃
 │ ~   │ @   │ { ¤ │ } ¢ │ ( ¥ │ ) € │ = £ │ <   │ >   │ [   │ ]   │ ! ¡ │ ` ¨ ┃  space  ┃
 ┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
 ┃       ┃ \   │ *   │ +   │     │     │     │     │   Ç │     │     │ ?   │ ^   ┃ Enter ┃
 ┃Tab ↹  ┃ : / │ ,   │ .   │ P   │ Y   │ F   │ G   │ C ç │ R   │ L   │ ; ¿ │ #   ┃   ⏎   ┃
 ┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
 ┃        ┃     │     │     │     │     │     │     │     │     │     │ _   │ &   ┃      ┃
 ┃Ctrl    ┃ A   │ O   │ E   │ U   │ I   │ D   │ H ← │ T ↓ │ N ↑ │ S → │ -   │ |   ┃      ┃
 ┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
 ┃      ┃     │ " ” │     │     │     │     │     │     │     │     │     ┃              ┃
 ┃Shift⇧┃ /   │ ' “ │ Q   │ J   │ K   │ X   │ B   │ M   │ W   │ V   │ Z   ┃Shift ⇧       ┃
 ┣━━━━━━┻┳━━━━┷━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━╈━━━━━┻┳━━━━━━┳━━━━━━┫
 ┃       ┃       ┃       ┃ ␣                               ⍽ ┃      ┃      ┃      ┃      ┃
 ┃Caps ⇬ ┃ Fn    ┃Alt    ┃ ␣           Space               ⍽ ┃AltGr ┃Ctrl  ┃RWin  ┃      ┃
 ┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━┻━━━━━━┻━━━━━━┻━━━━━━┛

 ANSI

 ┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
 │ %   │ $   │ 7   │ 5   │ 3   │ 1   │ 9   │ 0   │ 2   │ 4   │ 6   │ 8   │ ´ ˇ ┃ ⌫ Back  ┃
 │ ~   │ @   │ { ¤ │ } ¢ │ ( ¥ │ ) € │ = £ │ <   │ >   │ [   │ ]   │ ! ¡ │ ` ¨ ┃  space  ┃
 ┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┯━━━━━━━┩
 ┃       ┃ \   │ *   │ +   │     │     │     │     │   Ç │     │     │ ?   │ ^   │  &    │
 ┃Tab ↹  ┃ : / │ ,   │ .   │ P   │ Y   │ F   │ G   │ C ç │ R   │ L   │ ; ¿ │ #   │  |    │
 ┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┲━━━━┷━━━━━━━┪ 
 ┃        ┃     │     │     │     │     │     │     │     │     │     │ _   ┃   Enter    ┃
 ┃Ctrl    ┃ A   │ O   │ E   │ U   │ I   │ D   │ H ← │ T ↓ │ N ↑ │ S → │ -   ┃     ⏎      ┃
 ┣━━━━━━━━┻━━━┱─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┻━━━━━━━━━━━━┫
 ┃            ┃ " ” │     │     │     │     │     │     │     │     │     ┃              ┃
 ┃Shift ⇧     ┃ ' “ │ Q   │ J   │ K   │ X   │ B   │ M   │ W   │ V   │ Z   ┃Shift ⇧       ┃
 ┣━━━━━━━┳━━━━┻━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━╈━━━━━┻┳━━━━━━┳━━━━━━┫
 ┃       ┃       ┃       ┃ ␣                               ⍽ ┃      ┃      ┃      ┃      ┃
 ┃Caps ⇬ ┃ Fn    ┃Alt    ┃ ␣           Space               ⍽ ┃AltGr ┃Ctrl  ┃RWin  ┃      ┃
 ┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━┻━━━━━━┻━━━━━━┻━━━━━━┛



## Installation
first clone this repo 
```sh
git clone git@gitlab.com:nicoandresr/my-awesome-dvorak.git ~/.config/dvorak
```
and copy the `us_dvpjs` to `/usr/share/X11/xkb/symbols/us_dvpjs` with sudo

```shell
sudo cp ~/.config/dvorak/us_dvpjs /usr/share/X11/xkb/symbols/us_dvpjs
```

Then, set the keyboard layout with

```shell
setxkbmap us_dvpjs
```

To persist changes through restarts add this command to your `.xprofile`
```shell
echo "setxkbmap us_dvpjs" >> .xprofile
```


enjoy it.

## Mac users
```
open ~/.config/dvorak 
```
copy the `dvp_js.bundle` into `/Library/Keyboard Layouts/` (open it, in finder press 'cmd+shift+g')

or in shell do

```sh
sudo cp -R ~/.config/dvorak/dvp_js.bundle/ /Library/Keyboard\ Layouts/dvp_js.bundle
```

### Drawing lines
 
         0123456789abcdef | │╎┆┊╵╷╽ ─ ╴╶ ╼ ╌ ┄ ┈ | Common elements:
  U+250x ─━│┃┄┅┆┇┈┉┊┋┌┍┎┏ | ┃╏┇┋╹╻╿ ━ ╸╺ ╾ ╍ ┅ ┉ |
  U+251x ┐┑┒┓└┕┖┗┘┙┚┛├┝┞┟ | ┌┍┎┏ ┐┑┒┓ ├┤┝┥ ┼╋┿╂  | ┌┬┐┏┳┓╔╦╗┍┯┑╒╤╕┎┰┒╓╥╖
  U+252x ┠┡┢┣┤┥┦┧┨┩┪┫┬┭┮┯ | └┕┖┗ ┘┙┚┛ ┟┧┢┪ ┽╀┾╁  | ├┼┤┣╋┫╠╬╣┝┿┥╞╪╡┠╂┨╟╫╢
  U+253x ┰┱┲┳┴┵┶┷┸┹┺┻┼┽┾┿ | ┬┮┯┭ ┰┲┳┱ ┠┨┣┫ ╊╈╉╇  | └┴┘┗┻┛╚╩╝┕┷┙╘╧╛┖┸┚╙╨╜
  U+254x ╀╁╂╃╄╅╆╇╈╉╊╋╌╍╎╏ | ┴┶┷┵ ┸┺┻┹ ┞┦┡┩ ╃╄╆╅  | ─│ ━┃ ═║
  U+255x ═║╒╓╔╕╖╗╘╙╚╛╜╝╞╟ | ╔╦╗╒╤╕╓╥╖            |
  U+256x ╠╡╢╣╤╥╦╧╨╩╪╫╬╭╮╯ | ╠╬╣╞╪╡╟╫╢ ═ ║ ╱╳╲ ╭╮ |
  U+257x ╰╱╲╳╴╵╶╷╸╹╺╻╼╽╾╿ | ╚╩╝╘╧╛╙╨╜         ╰╯ |
