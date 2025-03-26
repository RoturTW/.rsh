# me

Get user information

- Retrieves information about the current user

## Usage

```txt
username@system ~ % me [property]
```

## Example

```txt
username@system ~ % me username
myusername

username@system ~ % me system
mysystem
```

## Notes

- Retrieves a specific property from the user information object
- Returns the value of the specified property
- No property specified returns an error or all properties
- Common properties include: username, system, id
