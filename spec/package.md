# package

Manage system packages

- Install, uninstall, and view system packages

## Usage

```txt
username@system ~ % package [action] [package_name/url]
```

## Actions

- `help`: Display help information
- `viewall`: List all packages available in the official store
- `install`: Install a package from the official store
- `uninstall`: Remove an installed package
- `unofficial`: Install a package from a specified URL
- `viewinstalled`: List all installed packages
- `info`: Show information about a package

## Examples

```txt
username@system ~ % package viewall
package1
package2
package3
...

username@system ~ % package install mypackage
Fetching Package Code
Downloaded Package (1024 Bytes)
Added Package to /Packages

username@system ~ % package uninstall mypackage
Package deleted

username@system ~ % package unofficial https://example.com/mypackage.pkg
Fetching Package Code
Downloaded Package (1024 Bytes)
Added Package to /Packages
```

## Notes

- Packages are stored in the user's /Packages directory
- The system creates the directory if it doesn't exist
- A package not found message is displayed if the specified package doesn't exist 