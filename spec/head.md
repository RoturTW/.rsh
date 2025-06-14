# head

Display first lines of data

- Shows the first n lines of text data

## Usage

```txt
username@system ~ % head num data
```

## Arguments

- `num`: Number of lines to display from the beginning
- `data`: Text data to process

## Examples

```txt
username@system ~ % head 3 "Line 1\nLine 2\nLine 3\nLine 4\nLine 5"
Line 1
Line 2
Line 3

username@system ~ % head 2 "First\nSecond\nThird"
First
Second
```

## Notes

- If the data has fewer lines than requested, all lines are displayed
- Newlines in the data string are interpreted as line separators
- Useful for previewing the beginning of large text data
