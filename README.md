# wayshot

Screenshot utility that combines the powers of
[grim](https://github.com/emersion/grim) and [slurp](https://github.com/emersion/slurp).

## Usage

```
$ wayshot -h
Usage: wayshot [options...] [filename]

Options:
  -s      Select a region to capture
  -w      Select a window (only in Sway)
  -d <n>  Delay by n seconds
  -c      Include cursors in the screenshot
  -h      Show this help message
```

## Dependencies

Required:

  * [grim](https://github.com/emersion/grim)
  * [slurp](https://github.com/emersion/slurp)

Optional:

  * [jq](https://stedolan.github.io/jq/) - window selection in [Sway](https://swaywm.org/)
