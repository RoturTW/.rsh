# if

Conditionally run rush code

- Runs a rush script only if the condition is true

## Usage

```txt
username@system ~ % if (condition) then {command}
```

## Examples

```txt
username@system ~ % if (fileExists hello.txt) then { cat hello.txt } else { touch hello.txt ; studio hello.txt }
```

This code would check to see if a file exists
if it doesn't: make it in the current directory and then open it in "studio" which is origin's text editor (can be swapped out for other editors)
if it does: cat it to the terminal output
