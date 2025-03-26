# Help Command

The `help` command displays documentation for RSH commands and features.

## Usage

```bash
help [command]
```

## Arguments

- `command` (optional): The name of a specific command to get help for. If omitted, displays general help information.

## Examples

```bash
help          # Display general help information
help ls       # Display help for the ls command
help calc     # Display help for the calc command
```

## Notes

- The help command pulls directly from the specification documentation
- Each command's documentation includes:
  - Description
  - Usage syntax
  - Examples
  - Notes and special considerations
- The documentation is organized alphabetically in the spec directory
- You can also view the full specification index at `SPEC_INDEX.md` 