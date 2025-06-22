# me

Get user account information

- Returns a key from the rotur user's account

## Usage

```txt
username@system ~ % me key
```

## Examples

```txt
username@system ~ % me username
myusername

username@system ~ % me theme
dark
```

## Notes

- Retrieves a specific key from the current rotur user's account object
- Returns the value associated with the specified key
- Common keys include: username, theme, id, email, preferences
- See [rotur account objects](https://docs.rotur.dev/my-account/rotur-account-objects) for available keys
