# tail

Display last lines of data

- Shows the last n lines of text data

## Usage

```txt
username@system ~ % tail num data
```

## Arguments

- `num`: Number of lines to display from the end
- `data`: Text data to process

## Examples

```txt
username@system ~ % tail 3 "Line 1\nLine 2\nLine 3\nLine 4\nLine 5"
Line 3
Line 4
Line 5

username@system ~ % tail 2 "First\nSecond\nThird"
Second
Third
```

## Notes

- If the data has fewer lines than requested, all lines are displayed
- Newlines in the data string are interpreted as line separators
- Useful for viewing the end of large text data or log files
