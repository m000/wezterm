# `wezterm.strftime_utc(format)`

*Since: nightly builds only*

Formats the current UTC date/time into a string using [the Rust chrono
strftime syntax](https://docs.rs/chrono/0.4.19/chrono/format/strftime/index.html).

```lua
local wezterm = require 'wezterm';

local date_and_time = wezterm.strftime_utc("%Y-%m-%d %H:%M:%S");
wezterm.log_info(date_and_time);
```

See also [strftime](strftime.md).
