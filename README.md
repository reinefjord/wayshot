# wayshot

A screenshot utility that combines the powers of
[grim](https://github.com/emersion/grim) and [slurp](https://github.com/emersion/slurp).


## Usage

```
$ wayshot -h
Usage: wayshot [options...] [filename]

Use - as filename to write the screenshot to stdout.

Options:
  -s      Select a region to capture
  -w      Select a window (only in sway)
  -d <n>  Delay by n seconds
  -c      Save screenshot to clipboard
  -x      Include cursors in the screenshot
  -h      Show this help message
```


## Dependencies

Required:

  * [grim](https://github.com/emersion/grim)
  * [slurp](https://github.com/emersion/slurp)

Optional:

  * [jq](https://github.com/stedolan/jq) - window selection in [sway](https://github.com/swaywm/sway)
  * [wl-clipboard](https://github.com/bugaevc/wl-clipboard) - save to clipboard
