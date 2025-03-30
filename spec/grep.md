# grep

Search for patterns in files or text streams

- Find lines matching a pattern in files or piped input
- Supports regular expressions for powerful text searching

## Usage

```txt
username@system ~ % grep [flags] pattern [data...]
```

## Flags

- `-i`: Ignore case distinctions
- `-v`: Invert match (select non-matching lines)
- `-n`: Prefix each line with line number
- `-c`: Only print a count of matching lines

## Examples

```txt
username@system ~ % grep error (cat log.txt)
[2023-05-10] error: connection failed
[2023-05-11] error: timeout occurred

username@system ~ % grep Terminal (ps)
20 Terminal

username@system ~ % grep -i hello (cat file.txt)
Hello World
HELLO everyone
hello there
```
