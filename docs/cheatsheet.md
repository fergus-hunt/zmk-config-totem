# TOTEM Cheatsheet

Search this page (Cmd+F) for a character, its name, or an action, like `~`, `tilde`, `pipe`, `undo`, `volume`, or `bluetooth`.

**How to read it:** "**Sym** + `Z`" means *hold the Sym thumb, then press the key that is `Z` on the base layer*.

## Thumb keys

```
        LEFT THUMBS                       RIGHT THUMBS
   ┌───────┬───────┬───────┐     ┌───────┬───────┬───────┐
   │  Esc  │  Tab  │ Space │     │ Enter │ Bksp  │  F19  │  ← tap
   │  FUN  │  NAV  │       │     │  SYM  │  NUM  │ HYPER │  ← hold
   └───────┴───────┴───────┘     └───────┴───────┴───────┘
     outer   middle  inner         inner   middle  outer
```

| Hold this thumb | Layer | Tap gives |
|---|---|---|
| Left outer (Esc) | **Fun**: F-keys, Bluetooth | Esc |
| Left middle (Tab) | **Nav**: arrows, media, copy/paste | Tab |
| Right inner (Enter) | **Sym**: symbols | Enter / Return |
| Right middle (Backspace) | **Num**: numbers, brackets | Backspace |
| Right outer | **Hyper** (Shift+Ctrl+Alt+Cmd) | F19 |

> **Tip:** Layer thumbs turn on instantly when your next key is on the **opposite** hand. For a key on the **same** hand as the thumb, such as Nav's media keys on the left, hold the thumb a moment (~180 ms) before you press it.

---

## Layers

### Base

```
       ┌─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┐
       │  Q  │  W  │  E  │  R  │  T  │   │  Y  │  U  │  I  │  O  │  P  │
       ├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
       │  A  │  S  │  D  │  F  │  G  │   │  H  │  J  │  K  │  L  │  ;  │
       │ctrl │ alt │ cmd │shift│     │   │     │shift│ cmd │ alt │ctrl │  ← hold
 ┌─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┐
 │ Sft │  Z  │  X  │  C  │  V  │  B  │   │  N  │  M  │  ,  │  .  │  /  │ Sft │
 └─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────┘
                   │ Esc │ Tab │Space│   │Enter│Bksp │ F19 │
                   │ FUN │ NAV │     │   │ SYM │ NUM │HYPER│  ← hold
                   └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

### Sym (hold Enter)

```
       ┌─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┐
       │  {  │  &  │  *  │  (  │  }  │   │     │     │     │     │     │
       ├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
       │  :  │  $  │  %  │  ^  │  +  │   │     │shift│ cmd │ alt │ctrl │
 ┌─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┐
 │  ~  │  "  │  !  │  @  │  #  │  |  │   │     │     │     │     │     │     │
 └─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────┘
                   │  (  │  )  │  _  │   │ ▓▓▓ │     │     │
                   └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

### Num (hold Backspace)

```
       ┌─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┐
       │  [  │  7  │  8  │  9  │  ]  │   │     │     │     │     │     │
       ├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
       │  ;  │  4  │  5  │  6  │  =  │   │     │shift│ cmd │ alt │ctrl │
 ┌─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┐
 │  `  │  '  │  1  │  2  │  3  │  \  │   │     │     │     │     │     │     │
 └─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────┘
                   │  .  │  0  │  -  │   │     │ ▓▓▓ │     │
                   └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

### Nav (hold Tab)

```
       ┌─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┐
       │ ⏮   │ ⏯   │ ⏭   │cmd `│cmd ⇥│   │undo │ cut │copy │paste│redo │
       ├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
       │ctrl │ alt │ cmd │shift│ctl ↑│   │  ←  │  ↓  │  ↑  │  →  │caps │
 ┌─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┐
 │mute │vol -│vol +│ctl ←│ctl ↓│ctl →│   │home │pg dn│pg up│ end │ ins │     │
 └─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────┘
                   │     │ ▓▓▓ │     │   │Enter│Bksp │HYPER│
                   └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

### Fun (hold Esc)

```
       ┌─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┐
       │ F11 │ F12 │ F13 │ F14 │ F15 │   │ BT0 │ BT1 │ BT2 │ BT3 │BTclr│
       ├─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┤
       │ F6  │ F7  │ F8  │ F9  │ F10 │   │     │shift│ cmd │ alt │ctrl │
 ┌─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┐
 │caps │ F1  │ F2  │ F3  │ F4  │ F5  │   │ F16 │ F17 │ F18 │ F19 │ F20 │     │
 └─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────┘
                   │ ▓▓▓ │     │     │   │USB/ │FUN2 │     │
                   │     │     │     │   │ BLE │     │     │
                   └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

**Fun2** (hold Esc, then also hold Backspace) has the same F1–F20 keys as Fun, without the Bluetooth, Caps, and USB/BLE keys.

---

## Find a key: how to press it

### Symbols

| Key | Name | How to press |
|---|---|---|
| `!` | exclamation, bang | **Sym** + `X` |
| `@` | at | **Sym** + `C` |
| `#` | hash, pound, number sign | **Sym** + `V` |
| `$` | dollar | **Sym** + `S` |
| `%` | percent | **Sym** + `D` |
| `^` | caret, hat | **Sym** + `F` |
| `&` | ampersand, and | **Sym** + `W` |
| `*` | asterisk, star | **Sym** + `E` |
| `(` | left paren, open parenthesis | **Sym** + `R`, or **Sym** + Esc thumb |
| `)` | right paren, close parenthesis | **Sym** + Tab thumb |
| `{` | left brace, open curly | **Sym** + `Q` |
| `}` | right brace, close curly | **Sym** + `T` |
| `[` | left bracket, open square | **Num** + `Q` |
| `]` | right bracket, close square | **Num** + `T` |
| `<` | less than, left angle | Shift + `,` (hold `F` or `J` for Shift) |
| `>` | greater than, right angle | Shift + `.` |
| `_` | underscore | **Sym** + Space thumb |
| `-` | minus, hyphen, dash | **Num** + Space thumb |
| `+` | plus | **Sym** + `G` |
| `=` | equals | **Num** + `G` |
| `:` | colon | **Sym** + `A` |
| `;` | semicolon | Tap `;` (base), or **Num** + `A` |
| `'` | single quote, apostrophe | **Num** + `Z` |
| `"` | double quote | **Sym** + `Z` |
| `` ` `` | backtick, grave | **Num** + bottom-left outer key |
| `~` | tilde | **Sym** + bottom-left outer key |
| `\|` | pipe, vertical bar | **Sym** + `B` |
| `\` | backslash | **Num** + `B` |
| `/` | slash, forward slash | Tap `/` (base) |
| `?` | question mark | Shift + `/` |
| `,` | comma | Tap `,` (base) |
| `.` | period, dot, full stop | Tap `.` (base), or **Num** + Esc thumb |

### Numbers

| Key | How to press |
|---|---|
| `0` | **Num** + Tab thumb |
| `1` `2` `3` | **Num** + `X` `C` `V` |
| `4` `5` `6` | **Num** + `S` `D` `F` |
| `7` `8` `9` | **Num** + `W` `E` `R` |

### Editing and navigation

| Action | How to press |
|---|---|
| ← Left arrow | **Nav** + `H` |
| ↓ Down arrow | **Nav** + `J` |
| ↑ Up arrow | **Nav** + `K` |
| → Right arrow | **Nav** + `L` |
| Home | **Nav** + `N` |
| End | **Nav** + `.` |
| Page Down | **Nav** + `M` |
| Page Up | **Nav** + `,` |
| Insert | **Nav** + `/` |
| Undo | **Nav** + `Y` |
| Cut | **Nav** + `U` |
| Copy | **Nav** + `I` |
| Paste | **Nav** + `O` |
| Redo | **Nav** + `P` |
| Caps Lock | **Nav** + `;`, or **Fun** + bottom-left outer key |
| Enter / Return | Tap right inner thumb |
| Backspace / Delete | Tap right middle thumb |
| Tab | Tap left middle thumb |
| Escape | Tap left outer thumb |
| Space | Tap left inner thumb |

### Windows, apps and macOS

| Action | How to press |
|---|---|
| App switcher (Cmd+Tab) | **Nav** + `T` |
| Cycle windows of the same app (Cmd+\`) | **Nav** + `R` |
| Mission Control (Ctrl+↑) | **Nav** + `G` |
| App Exposé (Ctrl+↓) | **Nav** + `V` |
| Previous desktop/space (Ctrl+←) | **Nav** + `C` |
| Next desktop/space (Ctrl+→) | **Nav** + `B` |
| Hyper (Shift+Ctrl+Alt+Cmd) | Hold right outer thumb |
| F18 | **Fun** + `,` |
| F19 | Tap right outer thumb, or **Fun** + `.` |

### Media and volume

| Action | How to press |
|---|---|
| Play / Pause | **Nav** + `W` |
| Previous track | **Nav** + `Q` |
| Next track | **Nav** + `E` |
| Mute | **Nav** + bottom-left outer key |
| Volume down | **Nav** + `Z` |
| Volume up | **Nav** + `X` |

### Modifiers

| Modifier | Hold on base | Hold on a layer |
|---|---|---|
| Ctrl / Control | `A` or `;` | **Nav** + `A`; **Sym/Num/Fun** + `;` |
| Alt / Option | `S` or `L` | **Nav** + `S`; **Sym/Num/Fun** + `L` |
| Cmd / GUI / Super | `D` or `K` | **Nav** + `D`; **Sym/Num/Fun** + `K` |
| Shift | Bottom-left/right outer key, or `F` / `J` | **Nav** + `F`; **Sym/Num/Fun** + `J` |

On the Sym, Num and Fun layers the right home row is plain modifiers, so you can make combos like **Cmd+[**: hold **Num**, hold `K` (Cmd), then press `Q`.

### Function keys

| Key | How to press |
|---|---|
| F1–F5 | **Fun** + `Z` `X` `C` `V` `B` |
| F6–F10 | **Fun** + `A` `S` `D` `F` `G` |
| F11–F15 | **Fun** + `Q` `W` `E` `R` `T` |
| F16–F20 | **Fun** + `N` `M` `,` `.` `/` |

### Bluetooth and connection

| Action | How to press |
|---|---|
| Bluetooth profile 0 | **Fun** + `Y` |
| Bluetooth profile 1 | **Fun** + `U` |
| Bluetooth profile 2 | **Fun** + `I` |
| Bluetooth profile 3 | **Fun** + `O` |
| Clear current Bluetooth pairing | **Fun** + `P` |
| Toggle output USB ↔ Bluetooth | **Fun** + Enter thumb |
