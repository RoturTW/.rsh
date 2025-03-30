# ps

Display information about active processes

- Shows snapshots of current processes running on the system
- Useful for monitoring system resources and troubleshooting

## Usage

```txt
username@system ~ % ps [flags]
```

## Flags

- `-x`: Include processes without controlling terminals
- `-p`: List all process IDs with the specified name

## Examples

```txt
username@system ~ % ps -x
20 Terminal
18 Files
12 Quick_Settings
11 Dock
10 Desktop

username@system ~ % ps -p Terminal
20
```
