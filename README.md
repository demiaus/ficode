# ficode - Finnish xkb layout for coding

## Quick Start

- Clone repo
```
git clone https://github.com/krumeluu/ficode && cd ficode
```
- Stick the contents of `ficode` file to the end of `/usr/share/X11/xkb/symbols/fi` manually or by running
```
sudo su -c 'cat ficode >> /usr/share/X11/xkb/symbols/fi'
```
- Manually insert the following after the Finnish variants in `/usr/share/X11/xkb/rules/base.extras.xml` and `/usr/share/X11/xkb/rules/evdev.extras.xml`

```
        <variant>
          <configItem popularity="exotic">
            <name>ficode</name>
            <description>Finnish (Code)</description>
          </configItem>
        </variant>
```

- Load keymap
```
setxkbmap -config xkb.conf
```

### Default layer
```
,---,---,---,---,---,---,---,---,---,---,---,---,---,-------,
| ` | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | - | = | <-    |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-----|
| ->| | q | w | e | r | t | y | u | i | o | p | [ | ] |     |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'|    |
| Esc  | a | s | d | f | g | h | j | k | l | ö | ä | ' |    |
|----,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'---'----|
|    | < | z | x | c | v | b | n | m | , | . | / |          |
|----'-,-',--'--,'---'---'---'---'---'---'-,-'---',--,------|
| ctrl |  | alt |                          |altgr |  | ctrl |
'------'  '-----'--------------------------'------'  '------'
```

### Shift layer
```
,---,---,---,---,---,---,---,---,---,---,---,---,---,-------,
| ~ | ! | " | # | $ | % | ^ | & | * | ( | ) | _ | + | <-    |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-----|
| ->| | Q | W | E | R | T | Y | U | I | O | P | { | } |     |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'|    |
| Esc  | A | S | D | F | G | H | J | K | L | Ö | Ä | ? |    |
|----,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'---'----|
|    | > | Z | X | C | V | B | N | M | ; | : | \ |          |
|----'-,-',--'--,'---'---'---'---'---'---'-,-'---',--,------|
| ctrl |  | alt |                          |altgr |  | ctrl |
'------'  '-----'--------------------------'------'  '------'
```

### AltGr layer
```
,---,---,---,---,---,---,---,---,---,---,---,---,---,-------,
| ~ | " | @ | £ | ¤ | ‰ | ^ |   |   |   | ° | ˇ |   | <-    |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-----|
| ->| | q | w | € | r | þ | y | u | i | œ | p | [ | ' |     |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'|    |
| Esc  | å | s | d | f | g | h | j | k | l | ö | æ | ` |    |
|----,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'---'----|
|    | | | ʒ | × | c | v | b | ŋ | µ | , | . | – |          |
|----'-,-',--'--,'---'---'---'---'---'---'-,-'---',--,------|
| ctrl |  | alt |                          |altgr |  | ctrl |
'------'  '-----'--------------------------'------'  '------'
```
