# upload

Upload a file from the local system

- Opens a file picker to upload a file to the system
- Can specify a destination directory

## Usage

```txt
username@system ~ % upload [destination_directory]
```

## Examples

```txt
username@system ~ % upload
[File picker opens]
Uploaded 1024 Bytes Successfully

username@system ~ % upload /user/username/documents
[File picker opens]
Uploaded 1024 Bytes Successfully
```

## Notes

- If no destination is specified, the file is saved to the Downloads directory
- Shows file size after successful upload
- Checks if the file size is within allowed limits before uploading
- Handles both binary and text files
