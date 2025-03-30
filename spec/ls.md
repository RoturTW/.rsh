# ls

List directory contents

- Lists files and directories in the current or specified directory
- Shows file IDs, names, and extensions
- Can accept flags for modified behavior

## Usage

```txt
username@system ~ % ls [directory] [flags]
```

## Flags

- `-j`: Display raw directory data instead of formatted output
- `-id`: Show file IDs

## Examples

```txt
username@system ~ % ls
ROOT (All) | Total Files: (125)
/Name
...

username@system ~ % ls /path/to/directory
directory | Total Files: (10)
/Name
...

username@system ~ % ls -j
[raw JSON data of directory contents]
```
