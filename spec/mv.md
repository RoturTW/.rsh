# mv

Move file

- Moves a file from one location to another

## Usage

```txt
username@system ~ % mv source_file destination_directory
```

## Examples

```txt
username@system ~ % mv document.txt /user/username/documents
Moved file to: /user/username/documents

username@system ~ % mv 42 /user/username/documents
Moved file to: /user/username/documents
```

## Notes

- Can specify the source file by name/path or by file ID
- The destination must be an existing directory
- Returns errors if the source file doesn't exist or the destination directory doesn't exist 