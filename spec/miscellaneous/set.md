# set

Set JSON value

- Sets a value in a JSON structure

## Usage

```txt
username@system ~ % set key json_string value
```

## Example

```txt
username@system ~ % set name '{"id":123}' "John"
{"id":123,"name":"John"}
```

## Notes

- The first parameter is the key to set
- The second parameter is the JSON structure to modify
- The third parameter is the value to set for the key
- Returns the modified JSON structure
