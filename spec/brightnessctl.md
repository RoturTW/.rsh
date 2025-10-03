# brightnessctl

Adjust screen brightness

- Adjusts the screen brightness using `roturLink` or the canvas apis

## Usage

```txt
username@system ~ % brightnessctl cmd [args]
```

## Supported Commands

- `g` or `get`: Get the current brightness level
- `s` or `set`: Set the brightness level
- `m` or `max`: Get the maximum brightness level

## Examples

```txt
username@system ~ % brightnessctl get
50

username@system ~ % brightnessctl set 50
Updated device 'originDM'
```

## Notes

- The `roturLink` API is used by default
- The `canvas` API is used if `roturLink` is not available
