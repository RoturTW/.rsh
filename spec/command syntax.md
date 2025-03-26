# Command Syntax

RSH commands follow a simple syntax pattern:

```txt
command [arguments...]
```

## Command Substitution

You can use the output of one command as an argument for another command by wrapping the command in parentheses. This is called command substitution.

Example:

```bash
cbcopy (me "wallpaper")  # Copies the wallpaper URL to clipboard
```

The command inside the parentheses is executed first, and its output is used as an argument for the outer command.

## Quoting

Quotes are used to handle arguments that contain spaces or special characters:

- Single quotes (`'`) preserve the literal value of each character
- Double quotes (`"`) allow for variable expansion and command substitution

Examples:

```bash
echo "Hello World"    # Prints: Hello World
```

## Arguments

Arguments are separated by spaces and can be:

- Required arguments (must be provided)
- Optional arguments (can be omitted)
- Flags (start with -)
- Values (data to be processed)

## Examples

```bash
ls                  # List files in current directory
ls -r               # List raw file directory
echo "Hello World"  # Print text with spaces
cd /path/to/dir     # Change to specific directory
```

## Notes

- Commands are case-sensitive
- Multiple spaces between arguments are treated as a single space
- Arguments containing spaces must be quoted
- Flags can not be combined, they must be seperate
