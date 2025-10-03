# wallpaperctl

Change the desktop wallpaper

- Requests the system to change the desktop wallpaper

## Usage

```txt
username@system ~ % wallpaperctl [args]
```

## Supported Arguments

- `s` or `set`: Set the wallpaper
  - Accepts a URL

- `g` or `get`: Get the current wallpaper
  - Prints the URL of the current wallpaper

- `m` or `mode`: Set the wallpaper mode
  - Accepts `stretch`, `fit`, `fill`, `center`

## Examples

```txt
username@system ~ % wallpaperctl set https://example.com/image.jpg

username@system ~ % wallpaperctl get
https://example.com/image.jpg

username@system ~ % wallpaperctl mode fit
```

## Notes

- This command only accepts URLs
- The `fill` mode is used by default
