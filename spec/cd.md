# cd

Change directory

- Changes the current working directory
- Can navigate to a specific path or use special navigation syntax

## Usage

```txt
username@system ~ % cd [directory]
```

## Special Arguments

- No argument: Change to user's home directory
- `..`: Navigate to parent directory

## Examples

```txt
username@system ~ % cd
Set directory to: /user/username

username@system ~ % cd /path/to/directory
Set directory to: /path/to/directory

username@system ~ % cd ..
Set directory to: /path/to
```

## Notes

- Returns an error message if the specified directory doesn't exist
