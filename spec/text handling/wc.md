# wc

Word, line, character count

- Counts characters or Unicode code points in text

## Usage

```txt
username@system ~ % wc [flags] text
```

## Flags

- `-c`: Count characters (bytes)
- `-m`: Count Unicode code points

## Examples

```txt
username@system ~ % wc -c "Hello, world!"
13

username@system ~ % wc -m "Hello, 世界!"
10
```

## Notes

- Default behavior if no flag is specified depends on implementation
- Counts characters differently based on the flag used
