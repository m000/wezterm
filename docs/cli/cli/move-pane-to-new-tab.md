# `wezterm cli move-pane-to-new-tab`

*Since: nightly builds only*

*Run `wezterm cli move-pane-to-new-tab --help` to see more help*

Allows moving a pane into a new tab either in the same window or in a new window.

The default action is to move the current pane into a new tab in the same window.
The following arguments modify the behavior:

* `--new-window` - Create tab in a new window
* `--window-id WINDOW_ID` - Create the new tab in the specified window id rather than the current window.
* `--workspace WORKSPACE` - When using `--new-window`, use `WORKSPACE` as the name of the workspace for the newly created window rather than the default workspace name `"default"`.
* `--pane-id` - Specifies which pane to move. See also [Targeting Panes](index.md#targeting-panes).
