# ficode - Finnish xkb layout for coding



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

### Shift layer ficode-min
```
,---,---,---,---,---,---,---,---,---,---,---,---,---,-------,
| ~ | ! | ? | # | $ | % | ^ | & | * | ( | ) | _ | + | <-    |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-----|
| ->| | Q | W | E | R | T | Y | U | I | O | P | { | } |     |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'|    |
| Esc  | A | S | D | F | G | H | J | K | L | Ö | Ä | " |    |
|----,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'---'----|
|    | > | Z | X | C | V | B | N | M | ; | : | \ |          |
|----'-,-',--'--,'---'---'---'---'---'---'-,-'---',--,------|
| ctrl |  | alt |                          |altgr |  | ctrl |
'------'  '-----'--------------------------'------'  '------'
```

### Shift layer ficode-og
```
,---,---,---,---,---,---,---,---,---,---,---,---,---,-------,
| ~ | ! | ? | # | $ | % | ^ | & | * | ( | ) | _ | + | <-    |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-----|
| ->| | Q | W | E | R | T | Y | U | I | O | P | { | } |     |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'|    |
| Esc  | A | S | D | F | G | H | J | K | L | Ö | Ä | " |    |
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


## Quickstart

- Clone repo
```
$ git clone https://github.com/krumeluu/ficode && cd ficode
```
- Copy files
```
# cp ficode /usr/share/X11/xkb/symbols/
```
- Load keymap
```
$ setxkbmap -config ficode-min.conf
```
or
```
$setxkbmap -config ficode-og.conf
```

