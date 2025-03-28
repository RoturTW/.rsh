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

- `-r`: Display raw directory data instead of formatted output

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

username@system ~ % ls -r
[raw JSON data of directory contents]
```
