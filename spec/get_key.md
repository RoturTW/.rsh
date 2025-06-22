# get_key

Get JSON value

- Gets a value from a JSON structure by key

## Usage

```txt
username@system ~ % get_key key json_string
```

## Example

```txt
username@system ~ % get_key name '{"id":123,"name":"John"}'
John

username@system ~ % get_key id '{"id":123,"name":"John"}'
123
```

## Notes

- The first parameter is the key to retrieve
- The second parameter is the JSON structure to read from
- Returns the value associated with the specified key
- Returns empty or error if the key doesn't exist
