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
    - `app` + `<arrow>`: Snap tab/page in <arrow> direction
    - `os` + `<arrow>`: Snap app/window in <arrow> direction
    - `os` + `alt` + `<arrow>`: Move app/window to another desktop
- Use **tab key** to change focus
    - `tab`: Change focus between items on a single page, or indent, depending on focus
    - `app` + `tab`: Change focus between pages/tabs of a single app
    - `os` + `tab`: Change focus between apps of a single desktop
    - `os` + `alt` + `tab`: Change focus between desktops
    - Combine `shift` key to send focus the opposite way

## Changes from 'standard' layouts
- Rather than the `[`+`{` key, have a `(`/`{`/`[`. Reason: For programming, the parenthesis is most common, then curly brace, then square bracket.

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
    



