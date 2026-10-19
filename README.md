# InputActions KWin
[KWin](https://invent.kde.org/plasma/kwin) compositor plugin implementation.

[Installation instructions](https://wiki.inputactions.org/main/getting-started/installation/kwin.html)

## Window-switcher navigation

`plasma_window_switcher_active` is true while KWin's Alt+Tab switcher is open.
Use it as a `directional_keys.repeat_conditions` condition to stop navigation
when the switcher closes. See [the touchpad example](examples/window-switcher.yaml)
for swipe locking and native arrow-key row navigation. Finger counts, distances,
angles, and shortcuts can be adjusted in the configuration.

This project used to be a part of the [taj-ny/InputActions](https://github.com/taj-ny/InputActions) repository. The latest commit before the split is [1055fabc31d77d59a8f1e1910197c44934078bc4](https://github.com/taj-ny/InputActions/tree/1055fabc31d77d59a8f1e1910197c44934078bc4).

The [taj-ny/InputActions](https://github.com/taj-ny/InputActions) repository serves as a global issue tracker for all subprojects and a place for discussion.
