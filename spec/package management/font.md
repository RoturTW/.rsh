# font

Manage system fonts

- View, install, and use fonts

## Usage

```txt
username@system ~ % font [action] [font_name]
```

## Actions

- `help`: Display help information
- `viewall`: List all fonts available in the official store
- `viewinstalled`: List all installed fonts
- `install`: Install a font from the official store
- `cleardata`: Clear current font data from memory
- `use`: Set the currently used font

## Examples

```txt
username@system ~ % font viewall
font1
font2
font3
...

username@system ~ % font install myfont
Downloaded 1024 Bytes Successfully

username@system ~ % font use myfont
256 Characters
Loaded Font Successfully
```

## Notes

- Fonts are stored in the user's /Fonts directory
- The system creates the directory if it doesn't exist
- A 404 error is displayed if the specified font doesn't exist
- The system needs to load a font before it can be used 