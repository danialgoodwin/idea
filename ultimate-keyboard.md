# Ultimate Keyboard

Requirements:
- Minimize how much fingers need to stretch to reach keys
- More used keys should be closer to the 'home row'
- Easily customized by users

Features:
- Keys vertically-aligned. Reason: Better ergonomics, less reaching
- Meta keys: 'os', 'app', 'user', 'shift', 'function'
  - Use 'os' key for OS-provided app-external shortcuts. Examples: 'Snap window/app left/right', 'Show desktop', 'Change app focus', 'Minimize app', 'Screenshot', 'Search computer', 'Search apps', 'Open app'
  - Use 'app' key for app-created app-internal shortcuts. Examples: 'Copy', 'Paste', 'Cut', 'Undo', 'Print', 'Open', 'New', 'Exit'
  - Use 'user' key for user-created shortcuts
  - Use 'shift' for more functionality
  - Use 'function' for another layer of commands (or, cycle multiple layers)
- Thumb keys. Reason: Get more usage out of thumbs. Examples: 'space', 'enter', 'shift', and other meta keys. Maybe arrows? 
- The keyboard is split and angled. Reason: Better ergonomics, allows for more natural hand and arm positions

In order to simplify the keyboard layout, the following keys will be removed:
- 'Caps Lock'. Reason: Never needed
- 'Insert'. Reason: Very rarely needed
- 'Page Up'. Reason: Use 'alt+up' instead
- 'Page Down'. Reason: Use 'alt+down' instead
- 'Home'. Reason: Use 'alt+left' instead
- 'End'. Reason: Use 'alt+right' instead


Try to use minimum distinct keys for all shortcuts?

## Changes from 'standard' layouts
- Rather than the `[`+`{` key, have a `(`/`{`/`[`. Reason: For programming, the parenthesis is most common, then curly brace, then square bracket.



# Consistent (Unified) Philosophy
For modifier keys:
- The `operating system` has one or more `desktop`s.
- Each `desktop` has many `app`s.
- Each `app` usually has just one `window`, but can have multiple `window`s.
- Each `window` has zero or more `tab`s.

More:
- In general, **modifier keys** will affect a certain component/level/category
    - <no selection>: Common functionality for all pages/apps/windows
    - `app`: Commands that the app defines, affecting components with an app, including copy (app + c), paste (app + v), new tab (app + t), print (app + p), etc
    - `app + alt`: Select app-window's menu
    - `os`: Commands defined by the operating system within a single desktop, including affecting apps and global functionality
    - `os + alt`: Commands that affect desktops. Ex: new desktop, change desktop, remove desktop
    - `function`: Access a layer of less-used keys on a keyboard, and safe for users to create their own shortcuts/macros
        - Perhaps, also used to acces numpad on 60% keyboards
- Use **arrow keys** when something needs to move, NOT when navigating forward and backwards, NOR volume, NOR brightness
    - `<arrow>`: Move cursor, or page, depending on focus
    - `alt` + `<arrow>`: Move cursor either page-up, page-down, home, end
    - `alt` + `shift` + `<arrow>: Auto-scroll in <arrow direction>
    - `app` + `<arrow>`: Snap tab/page in <arrow> direction
    - `os` + `<arrow>`: Snap app/window in <arrow> direction
    - `os` + `alt` + `<arrow>`: Move app/window to another desktop
- Use **tab key** to change focus
    - `tab`: Change focus between items on a single page, or indent, depending on focus
    - `app` + `tab`: Change focus between pages/tabs of a single app
    - `os` + `tab`: Change focus between apps of a single desktop
    - `os` + `alt` + `tab`: Change focus between desktops
    - Combine `shift` key to send focus the opposite way

## Common tasks
_definitely up for changes_

| Hotkey | Action |
| ------ | ------ |
| `f1` | Show help |
| `f3` | Find next |
| `shift + f3` | Find previous |
| `app + a` | Select all items in component |
| `app + shift + a` | Find action... |
| `app + b` | Toggle bookmark current page |
| `app + shift + b` | Bookmark current page... |
| `app + alt + b` | Toggle show quick bookmarks |
| `app + alt + shift + b` | Show bookmarks as full page |
| `app + c` | Copy selection to clipboard |
| `app + shift + c` | Copy selection to clipboard... |
| `app + f` | Find in page... |
| `app + shift + f` | Find in app... |
| `app + g` | Go to... |
| `app + o` | Open file... |
| `app + p` | Print... |
| `app + q` | Quit app window |
| `app + shift + q` | Quit all app windows |
| `app + alt + q` | Quit other app windows |
| `app + s` | Save |
| `app + shift + s` | Save as... |
| `app + alt + s` | Toggle current tab as pinned |
| `app + t` | Open new tab |
| `app + shift + t` | Re-open last-closed tab |
| `app + alt + t` | Open new window |
| `app + v` | Paste clipboard |
| `app + shift + v` | Paste clipboard... |
| `app + alt + v` | Paste clipboard without formatting |
| `app + z` | Undo |
| `app + shift + z` | Redo |
| `app + f1` | Show app settings |
| `app + alt + f1` | Show app help |
| `app + ` |  |
| `app + ` | Zoom in, zoom out, zoom default |
| `app + ` |  |
| `os + ` |  |
| `os + ` |  |
| `os + q` | Quit, aka lock |
| `os + shift + q` | Quit, aka  |
| `os + f1` | Show OS settings |
| `os + alt + f1` | Show OS help |
| `os + backspace` | Exit; Close App |
| `os + ` |  |
| `os + ` |  |
| `os + ` | Toggle: Maximize app window |
| `os + ` | Minimize app window |
| `os + ` | Show calendar (includes current date, time, weather) |
| `os + ` |  |
| `os + ` |  |
| `os + ` |  |

## Common basic text editor tasks
_definitely up for changes_

| Hotkey | Action |
| ------ | ------ |
| `app + c` | Copy selection to clipboard; Copy line to clipboard |
| `app + d` | Duplicate selection; Duplicate line |
| `app + j` | Join lines |
| `app + r` | Find and replace... |
| `app + x` | Cut selection; Cut line |
| `app + backspace` | Remove word backwards |
| `app + alt + backspace` | Navigate to last edit location |
| `app + ` |  |

## Common rich text editor tasks
_definitely up for changes_

| Hotkey | Action |
| ------ | ------ |
| `app + b` | Toggle selected text as bold; Toggle line as bold |
| `app + i` | Toggle selected text as italic; Toggle line as italic |
| `app + j` | Toggle paragraph justify |
| `app + u` | Toggle selected text as underline; Toggle line as underline |
| `app + ` |  |

## Common (internet) browser tasks
_definitely up for changes_

| Hotkey | Action |
| ------ | ------ |
| `app + ` |  |
| `app + h` | Show quick history |
| `app + shift + h` | Show history in new page |
| `app + j` (should change this bc 'join lines' and 'justify' elsewhere) | Show downloads |
| `app + r` | Reload page |
| `app + ` |  |
| `app + ` |  |
| `app + ` | Rename selected item... |
| `app + ` |  |

## Common (file/media) browser tasks
_definitely up for changes_

| Hotkey | Action |
| ------ | ------ |
| `app + ` | Rename selected item... |
| `app + ` |  |
| `app + ` |  |
| `app + ` |  |


## Common IDE tasks
_definitely up for changes_

| Hotkey | Action | Note |
| ------ | ------ | ---- |
| `f2` | Navigate to next error |  |
| `shift + f2` | Navigate to previous error |  |
| `f5` | Run |  |
| `shift + f5` | Run... |  |
| `alt + up` | Navigate to previous function | Override 'page up' because this is more common |
| `alt + shift + up` | Move selected lines up |  |
| `alt + shift + down` | Move selected lines down |  |
| `app + ` |  |  |
| `app + q` | Show documentation | Override 'quit' because it is needed less and don't want to accidentally close |
| `app + r` | Rename... |  |
| `app + shift + r` |  |  |
| `app + ` |  |  |
| `app + ` |  |  |
| `app + ` |  |  |
| `app + ` |  |  |
| `app + ` |  |  |
| `app + w` | Expand selection |  |
| `app + shift + w` | Shrink selection |  |
| `app + /` | Toggle line comment |  |
| `app + shift + /` | Toggle block comment |  |
| `app + space` | Auto-complete |  |
| `app + shift + space` | Auto-complete... |  |
| `app + ` |  |  |

## Common 'modal' apps
Some apps have their main interaction to be non-text-input. In those cases, it would be benefitial and ergonomic to re-purpose the letters for different functionality, until text-input is needed again. For apps that commonly use mouse input, then it will be preferred to re-purpose letters on the left side of the keyboard.

Good examples: Gmail, vim, Vimium (aka, vim for chrome), games (have to hit <enter> in order to use letters in chat), media editors (Photoshop, Gimp, Audacity, Movie Maker)

Okay examples:
- Operating systems: By default, pressing letters does nothing. Only when focus is in a text-input box, then letters are sent to the app.
- Browsers: Same reason as above.


# Shortcuts

## Shortcuts (with arrow keys)
_Thinking about 60% keyboard with arrow keys._

    window-snap-left os + <left>
    window-snap-right os + <right>
    window-screen-left os + shift + <left>
    window-screen-right os + shift + <right>
    window-desktop-left os + mod + <left>
    window-desktop-right os + mod + <right>
    tab-snap-right app + <right>
    tab-snap-left app + <left>
    
    os-search os + f
    os-launch-app os + space
    os-volume-up os + f1
    os-volumn-down os + f2
    screen-brightness-up os + f3
    screen-brightness-down os + f4
    os-screenshot os + f5
    
    app-search app + f
    app-launch-window app + space
    app-volume-up app + f1
    app-volume-down app + f2
    app-screenshot app + f5 
    
    mouse-up nav + 8
    mouse-down nav + k
    mouse-left nav + u
    mouse-right nav + o
    back nav + left
    forward nav + right
    up nav + up
    page-up nav + e
    page-down nav + d
    end nav + f
    home nav + s


## Shortcuts (without arrow keys)
_Thinking about a 40% keyboard._

(living document)

    window-snap-right os + ]  // Unsure if we want to use extra symbol keys
    window-snap-left os + [
    window-snap-right os + <right>
    window-snap-left os + <left>
    



