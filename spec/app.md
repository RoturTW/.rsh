# app

Manage applications

- Install and uninstall applications

## Usage

```txt
username@system ~ % app [action] [app_name]
```

## Actions

- `help`: Display help information
- `install`: Install an application from the official store
- `uninstall`: Remove an installed application
- `stats`: Show application statistics

## Examples

```txt
username@system ~ % app help
app install name
// Installs an app from the official store
app uninstall
// deletes an app you have installed

username@system ~ % app install myapp
Fetching Application Code
Downloaded script.osl Successfully (1024 Bytes)
Downloaded icon.icn Successfully (256 Bytes)
Installed Application Into username/Applications

username@system ~ % app uninstall myapp
Application deleted
```

## Notes

- Applications are stored in the user's /Applications directory
- The system creates the directory if it doesn't exist
- A 404 error is displayed if the specified application doesn't exist
- Applications can include both script files and icons 